<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":239};
const content = `<path class="ukpql63qn"/><path class="jngbvrbel"/><path class="kpka-fb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:togetherai-icon" /></template>
<style>
.jngbvrbel {
  fill: var(--svg-color--caaef5, #caaef5);
  d: path("M8.583 31.91c-17.669 30.515-7.183 69.532 23.42 87.152c19.69 11.334 42.78 11.12 61.544 1.352l-31.9-55.257L66.4 62.43l31.97 55.21c8.45-5.34 15.699-12.69 21.046-21.927c17.669-30.516 7.183-69.533-23.42-87.153C65.386-9.06 26.251 1.395 8.583 31.91");
}

.kpka-fb6c {
  fill: var(--svg-color--fc4c02, #fc4c02);
  d: path("M127.986 238.15c35.34 0 63.988-28.562 63.988-63.797c0-22.668-11.73-42.497-29.596-53.816l-32.049 55.176l-4.745-2.74l31.97-55.21c-8.86-4.627-18.872-7.207-29.572-7.207c-35.341 0-63.989 28.562-63.989 63.797s28.648 63.797 63.989 63.797z");
}

.ukpql63qn {
  fill: var(--svg-color--ef2cc1, #ef2cc1);
  d: path("M247.415 31.93C229.747 1.414 190.61-9.04 160.005 8.575c-19.689 11.335-31.05 31.376-31.943 52.463l63.95.082l-.008 5.467h-63.946c.412 9.967 3.175 19.898 8.523 29.136c17.668 30.515 56.806 40.97 87.413 23.351c30.607-17.616 41.093-56.637 23.421-87.152z");
}

</style>
