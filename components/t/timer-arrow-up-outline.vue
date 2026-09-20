<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv2clbcus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-arrow-up-outline" /></template>
<style>
.zv2clbcus {
  fill: currentColor;
  d: path("M4.207 17.133q-1.86-1.866-1.86-4.533t1.861-4.538t4.523-1.87q1.185 0 2.248.403t1.898 1.128l.954-.954l.688.689l-.934.953q.725.835 1.137 1.902t.413 2.283q0 2.669-1.867 4.536T8.734 19t-4.527-1.867M18.884 19V6.916L17.4 8.4l-.708-.708L19.385 5l2.692 2.692l-.713.708l-1.48-1.479V19zM6.808 4.77v-1h3.884v1zm5.754 11.658q1.573-1.573 1.573-3.833t-1.573-3.831T8.73 7.192T4.908 8.765q-1.562 1.572-1.562 3.833q0 2.26 1.562 3.83Q6.469 18 8.729 18t3.833-1.572m-4.331-3.524h1V9.096h-1zm.5-.308");
}

</style>
