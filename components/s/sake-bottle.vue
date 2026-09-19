<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz5vqb9ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uz5vqb9ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sake-bottle" /></template>
