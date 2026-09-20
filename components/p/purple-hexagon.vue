<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6h71cw6d.css';
import '../../css/x/x1mdp195q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="h6h71cw6d"/><path class="x1mdp195q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:purple-hexagon" /></template>
