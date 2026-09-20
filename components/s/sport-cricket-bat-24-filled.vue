<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skdbdeqxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sport-cricket-bat-24-filled" /></template>
<style>
.skdbdeqxb {
  fill: currentColor;
  d: path("M17.027 10.086a2 2 0 0 0-.024.314v1.323c0 .596-.237 1.17-.659 1.592L8.32 21.338a2.25 2.25 0 0 1-3.182 0l-2.475-2.474a2.25 2.25 0 0 1 0-3.183l8.023-8.021a2.25 2.25 0 0 1 1.59-.66h1.314q.164-.002.324-.027zm2.116-7.694a1.75 1.75 0 0 1 2.342.12l.12.133a1.75 1.75 0 0 1 0 2.209l-.12.133l-3.719 3.717l-2.475-2.474l3.72-3.718z");
}

</style>
