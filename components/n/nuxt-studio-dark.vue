<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/il90q5pnk.css';
import '../../css/t/tey8c23jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":227,"height":32};
const content = `<g class="ft5dv1b6b"><path class="il90q5pnk"/><path class="tey8c23jn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nuxt-studio-dark" /></template>
