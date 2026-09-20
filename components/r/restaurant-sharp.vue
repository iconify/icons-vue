<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at63zliel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:restaurant-sharp" /></template>
<style>
.at63zliel {
  fill: currentColor;
  d: path("M7 22v-9.15q-1.275-.35-2.137-1.4T4 9V2h2v7h1V2h2v7h1V2h2v7q0 1.4-.862 2.45T9 12.85V22zm10 0v-8h-3V7q0-2.075 1.463-3.537T19 2v20z");
}

</style>
