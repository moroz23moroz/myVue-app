<template>
  <h1>Start!</h1>
  <button @click="addLikes">Like</button>
  <button @click="addDislikes">Dislike</button>
  <p>Количество лайков: {{ likes }}</p>
  <p>Количество дизлайков: {{ dislikes }}</p>
</template>

<script>
export default {
  data() {
    return {
      likes: 8,
      dislikes: 8,
    };
  },
  methods: {
    addLikes() {
      this.likes += 1;
    },
    addDislikes() {
      this.dislikes += 1;
    },
  },
};
</script>

<style></style>
