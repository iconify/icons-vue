<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l14n7kb1k.css';
import '../../css/h/hj5pjd6bf.css';
import '../../css/d/d4uf2sbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l14n7kb1k"/><path class="hj5pjd6bf wm-a"/><path class="d4uf2sbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:network-duo" /></template>
