<template>
  <div class="home">
    <b-container>
      <h1 class="text-center">Start your fitness journey.</h1>
      <RecommendedWorkout />
    </b-container>
  </div>
</template>

<script>
import RecommendedWorkout from '@/components/RecommendedWorkout.vue';

export default {
  components: {
    RecommendedWorkout,
  },
};

</script>
