<template>
  <v-app>
    <v-container class="pl-10 pb-10 pr-10 pt-8" fluid
      style="background-color:white">
      <h1>Quiz Suku Kata 1</h1>
      <LevelQuiz />
      <TambahGambar />
      <TambahSuara />
      <TambahJawabanQuiz />
      <ButtonUploadQuiz />
    </v-container>
  </v-app>
</template>

<script>
import LevelQuiz from '@/components/learningandquiz/LevelQuiz.vue';
import TambahGambar from '@/components/learningandquiz/TambahGambar.vue';
import TambahSuara from '@/components/learningandquiz/TambahSuara.vue';
import TambahJawabanQuiz from '@/components/learningandquiz/TambahJawabanQuiz.vue';
import ButtonUploadQuiz from '@/components/learningandquiz/ButtonUploadQuiz.vue';

export default {
  name: 'QuizSukuKata1',

  components: {
    LevelQuiz,
    TambahGambar,
    TambahSuara,
    TambahJawabanQuiz,
    ButtonUploadQuiz
  },

  data: () => ({
    item: [],
  }),
};
</script>

<style>
    .h2 {
        color: #FF5E3C;
    }
    h1 {
        color: #FF5E3C;
    }
</style>