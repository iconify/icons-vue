<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kms9obaci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:options-speaker-28-regular" /></template>
<style>
.kms9obaci {
  fill: currentColor;
  d: path("M21.938 13.679a.75.75 0 0 1 1.057.089A8.47 8.47 0 0 1 25 19.25a8.47 8.47 0 0 1-2.004 5.482a.75.75 0 0 1-1.146-.967a6.97 6.97 0 0 0 1.65-4.515a6.97 6.97 0 0 0-1.65-4.514a.75.75 0 0 1 .088-1.057m-5.221.543a.75.75 0 0 1 1.28.53v8.998a.75.75 0 0 1-1.28.53l-2.777-2.779H12a1 1 0 0 1-1-1v-.5H2.75a.75.75 0 0 1 0-1.5H11v-.5a1 1 0 0 1 1-1h1.94zm3.072 1.522a.75.75 0 0 1 1.053.131a5.48 5.48 0 0 1 1.157 3.375c0 1.27-.433 2.444-1.157 3.375a.75.75 0 1 1-1.184-.92c.527-.678.841-1.53.841-2.455a3.98 3.98 0 0 0-.84-2.453a.75.75 0 0 1 .13-1.053M10.25 3.5a3.75 3.75 0 0 1 3.675 3H25.25a.75.75 0 0 1 0 1.5H13.925a3.751 3.751 0 0 1-7.35 0H2.75a.75.75 0 0 1 0-1.5h3.825a3.75 3.75 0 0 1 3.675-3m0 1.5a2.25 2.25 0 1 0 0 4.5a2.25 2.25 0 0 0 0-4.5");
}

</style>
