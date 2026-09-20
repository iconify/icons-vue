<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/p5aswobnw.css';
import '../../css/w/w0e46ufpc.css';
import '../../css/j/j-mlh2z9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="p5aswobnw"/><path class="w0e46ufpc"/><path class="j-mlh2z9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam" /></template>
