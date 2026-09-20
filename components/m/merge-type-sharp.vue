<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgep7filf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:merge-type-sharp" /></template>
<style>
.hgep7filf {
  fill: currentColor;
  d: path("M16.985 19L11.5 13.516V5.952l-3.1 3.1l-.713-.713L12 4.025l4.308 4.308l-.714.713L12.5 5.952V13.1l5.192 5.192zm-9.97.006l-.707-.708l3.579-3.585l.713.714z");
}

</style>
