<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fxpjof0ho.css';
import '../../css/k/koqkggbqh.css';
import '../../css/x/xlau4cdnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fxpjof0ho"/><path class="koqkggbqh wm-a"/><path class="xlau4cdnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tent-duo" /></template>
