<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-9b9jbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moving-beds" /></template>
<style>
.y-9b9jbhr {
  fill: currentColor;
  d: path("M4.846 21q-.671 0-1.143-.472t-.472-1.144V4.616q0-.672.472-1.144T4.846 3h7.77q.67 0 1.143.472q.472.472.472 1.144v14.769q0 .67-.472 1.143q-.472.472-1.143.472zm-.615-9.206q.392-.39.902-.592T6.23 11h5q.588 0 1.098.202t.902.592V4.615q0-.269-.173-.442T12.616 4h-7.77q-.269 0-.442.173t-.173.443zm3.434-3.228Q7.23 8.133 7.23 7.5t.434-1.066Q8.098 6 8.73 6t1.066.434t.434 1.066t-.434 1.066T8.731 9t-1.066-.434M19 14.788l-.708-.688l1.595-1.6H16v-1h3.887l-1.595-1.6l.708-.689L21.788 12zM8.23 18.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2z");
}

</style>
