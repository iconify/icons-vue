<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufx-z5bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-arrow-right-24-filled" /></template>
<style>
.ufx-z5bla {
  fill: currentColor;
  d: path("M3 5.75A.75.75 0 0 1 3.75 5c2.663 0 5.258-.943 7.8-2.85a.75.75 0 0 1 .9 0C14.992 4.057 17.587 5 20.25 5a.75.75 0 0 1 .75.75V11q0 .507-.04.996a6.5 6.5 0 0 0-8.33 9.809l-.355.143a.75.75 0 0 1-.55 0C5.958 19.676 3 16 3 11zm20 11.746a5.5 5.5 0 1 0-11 0a5.5 5.5 0 0 0 11 0m-9 0a.5.5 0 0 1 .5-.5h4.793l-1.647-1.646a.5.5 0 0 1 .708-.707l2.5 2.5a.5.5 0 0 1 0 .707l-2.5 2.5a.5.5 0 0 1-.708-.708l1.647-1.646H14.5a.5.5 0 0 1-.5-.5");
}

</style>
