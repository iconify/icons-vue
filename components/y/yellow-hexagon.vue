<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upw6qkbvk.css';
import '../../css/x/x1mdp195q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="upw6qkbvk"/><path class="x1mdp195q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:yellow-hexagon" /></template>
