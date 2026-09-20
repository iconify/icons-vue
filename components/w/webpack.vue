<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":290};
const content = `<path class="qe8cf-b4o"/><path class="cf3ixq3_o"/><path class="j37p4rbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:webpack" /></template>
<style>
.cf3ixq3_o {
  fill: var(--svg-color--8ed6fb, #8ed6fb);
  d: path("m233.153 212.287l-100.902 57.14V224.99l62.889-34.632zm6.907-6.231V86.654l-36.902 21.3v76.8zm-217.6 6.23l100.903 57.094v-44.438l-62.889-34.584zm-6.907-6.23V86.654l36.903 21.3v76.8zm4.3-127.13l103.51-58.543v42.99L57.045 99.84l-.532.29zm215.86 0L132.251 20.382v42.99l66.27 36.515l.531.29z");
}

.j37p4rbhn {
  fill: var(--svg-color--1c78c0, #1c78c0);
  d: path("m123.363 214.847l-62.02-34.15v-67.574l62.02 35.792zm8.888 0l62.02-34.101v-67.623l-62.02 35.792zM65.497 105.298l62.31-34.246l62.26 34.246l-62.26 35.937z");
}

.qe8cf-b4o {
  fill: var(--svg-color--fff, #fff);
  d: path("m128 .048l128 72.405V217.31l-128 72.405L0 217.31V72.453z");
}

</style>
