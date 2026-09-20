<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhc46cb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-available-24-filled" /></template>
<style>
.fhc46cb1h {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-5.477 2A6.47 6.47 0 0 0 11 17.5c0 1.63.6 3.12 1.592 4.262q-1.193.24-2.592.24c-3.42 0-5.944-1.073-7.486-3.237a2.75 2.75 0 0 1-.51-1.596v-.92A2.25 2.25 0 0 1 4.253 14zm2.83 3.147a.5.5 0 1 0-.706.707l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 1 0-.707-.707L16.5 18.793zM10 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10");
}

</style>
