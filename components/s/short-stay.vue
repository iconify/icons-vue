<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ooiio1bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:short-stay" /></template>
<style>
.ooiio1bni {
  fill: currentColor;
  d: path("M9.73 9q-.632 0-1.065-.434Q8.23 8.133 8.23 7.5t.434-1.066Q9.098 6 9.73 6t1.066.434t.434 1.066t-.434 1.066Q10.364 9 9.731 9m4.087 11.182Q12.5 18.863 12.5 17t1.318-3.182T17 12.5t3.182 1.318T21.5 17t-1.318 3.182T17 21.5t-3.182-1.318m4.857-.96l.546-.547l-1.836-1.836v-2.723h-.77v3.046zM5.846 21q-.671 0-1.143-.472t-.472-1.144V4.616q0-.672.472-1.144T5.846 3h7.77q.67 0 1.143.472q.472.472.472 1.144v5.748q-.281.055-.521.14q-.24.087-.48.19V4.615q0-.269-.172-.442Q13.885 4 13.616 4h-7.77q-.269 0-.442.173t-.173.443v7.178q.392-.39.902-.592T7.23 11h6.073v.216q-1.16.748-1.914 1.8q-.755 1.051-1.063 2.346h-.096V13.5h-1v2h-2v1h2v2h.954v-1.038q.057.97.382 1.87t.88 1.668z");
}

</style>
