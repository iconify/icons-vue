<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iba-o7bgl.css';
import '../../css/f/fzrqn6dxq.css';
import '../../css/k/kuz0qbccj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="iba-o7bgl"/><path class="fzrqn6dxq"/><path class="kuz0qbccj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="unjs:node-fetch-native" /></template>
