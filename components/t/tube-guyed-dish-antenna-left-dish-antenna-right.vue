<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5d2v1bhr.css';
import '../../css/z/zisei9b2e.css';
import '../../css/w/wmejmsbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v5d2v1bhr"/><path class="zisei9b2e"/><path class="wmejmsbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:tube-guyed-dish-antenna-left-dish-antenna-right" /></template>
