<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f38w9glro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:router-off-20-regular" /></template>
<style>
.f38w9glro {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-.74-.739A2.5 2.5 0 0 1 14.5 18h-9a2.5 2.5 0 0 1 0-5h4v-1.556a2.25 2.25 0 0 1-1.642-2.879L6.635 7.342A4 4 0 0 0 6 9.5a.5.5 0 0 1-1 0c0-1.072.338-2.066.913-2.88L4.841 5.548A6.47 6.47 0 0 0 3.5 9.5a.5.5 0 0 1-1 0c0-1.764.61-3.384 1.628-4.665L2.146 2.854a.5.5 0 0 1 0-.708M5.5 14a1.5 1.5 0 0 0 0 3h9c.49 0 .922-.235 1.195-.598L13.293 14zm5.185-2.607q-.09.03-.185.051V13h1.793zM10 7a2.25 2.25 0 0 1 2.121 3l-.878-.878a1.25 1.25 0 0 0-1.115-1.115L9.25 7.13c.235-.083.487-.13.75-.13m0-2.5a5 5 0 0 1 5 5a.5.5 0 0 1-1 0a4 4 0 0 0-5.9-3.521l-.732-.732A5 5 0 0 1 10 4.5M10 2a7.5 7.5 0 0 1 7.5 7.5a.5.5 0 0 1-1 0A6.5 6.5 0 0 0 6.287 4.166l-.717-.717A7.47 7.47 0 0 1 10 2");
}

</style>
