<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j65ksvb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:u-turn-left-outline" /></template>
<style>
.j65ksvb3p {
  fill: currentColor;
  d: path("M16.558 20V9.385q0-1.823-1.281-3.104T12.173 5T9.069 6.28T7.79 9.386v4.988l2.08-2.08l.708.707l-3.288 3.288L4 13l.708-.708l2.08 2.081V9.385q0-2.25 1.568-3.818T12.173 4t3.818 1.567t1.567 3.817V20z");
}

</style>
