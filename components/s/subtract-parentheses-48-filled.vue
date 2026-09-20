<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u_ekf2wde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-parentheses-48-filled" /></template>
<style>
.u_ekf2wde {
  fill: currentColor;
  d: path("M13.433 10.682a1.5 1.5 0 1 0-1.866-2.349C6.959 11.995 4 17.653 4 24c0 6.348 2.959 12.005 7.567 15.667a1.5 1.5 0 1 0 1.866-2.349C9.511 34.201 7 29.394 7 24s2.51-10.2 6.433-13.318m23-2.349a1.5 1.5 0 0 0-1.866 2.35C38.489 13.798 41 18.605 41 24s-2.51 10.201-6.433 13.318a1.5 1.5 0 1 0 1.866 2.349C41.041 36.005 44 30.347 44 24c0-6.348-2.959-12.005-7.567-15.667M15.5 22.5a1.5 1.5 0 0 0 0 3h17a1.5 1.5 0 0 0 0-3z");
}

</style>
