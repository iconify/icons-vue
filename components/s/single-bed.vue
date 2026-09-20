<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrwogh6ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:single-bed" /></template>
<style>
.hrwogh6ev {
  fill: currentColor;
  d: path("M6.77 18h-.54l-.38-2H5v-3.39q0-.671.472-1.14q.472-.47 1.144-.47H7V8.615q0-.67.472-1.143Q7.944 7 8.616 7h6.769q.67 0 1.143.472q.472.472.472 1.143V11h.385q.67 0 1.143.472q.472.472.472 1.144V16h-.85l-.38 2h-.54l-.38-2h-9.7zm5.73-7H16V8.615q0-.269-.173-.442T15.385 8H12.5zM8 11h3.5V8H8.616q-.27 0-.443.173T8 8.615z");
}

</style>
