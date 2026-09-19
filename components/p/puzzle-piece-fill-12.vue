<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvedctbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gvedctbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:puzzle-piece-fill-12" /></template>
