<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx9qd_kyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-selection-outline" /></template>
<style>
.qx9qd_kyw {
  fill: currentColor;
  d: path("m12.192 20l-.707-.708l3.55-3.55l-3.55-3.55l.707-.708l3.55 3.55l3.55-3.55l.708.708l-3.55 3.55l3.55 3.55l-.708.708l-3.55-3.55zm-4.5 0v-1.23h1.231V20zM5.231 5.23H4q0-.507.362-.868T5.23 4zm2.461 0V4h1.231v1.23zm3.693 0V4h1.23v1.23zm3.692 0V4h1.23v1.23zm3.692 0V4q.508 0 .87.362T20 5.23zM5.231 18.77V20q-.508 0-.87-.362T4 18.77zM4 16.307v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zm14.77 0v-1.23H20v1.23z");
}

</style>
