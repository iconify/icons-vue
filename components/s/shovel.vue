<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf-mujbtt.css';
import '../../css/b/bvjkk-_ua.css';
import '../../css/g/g6oiphjjx.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/i/i2wianfxh.css';
import '../../css/g/gy-7c6b-p.css';
import '../../css/f/f0c1tgb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tf-mujbtt"/><path class="bvjkk-_ua"/><path class="g6oiphjjx"/><g class="jn8qy4bru"><path class="i2wianfxh"/><path class="gy-7c6b-p"/><path class="f0c1tgb3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:shovel" /></template>
