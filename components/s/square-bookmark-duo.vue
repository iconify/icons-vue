<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz4xt1bwd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e77ebfb5e.css';
import '../../css/f/f8t3o_b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz4xt1bwd secondary"/><g class="dt0cm9dhy primary"><path class="e77ebfb5e"/><path class="f8t3o_b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-bookmark-duo" /></template>
