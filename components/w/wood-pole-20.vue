<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj75j-log.css';
import '../../css/f/fdqwsub7z.css';
import '../../css/w/w58xql4qz.css';
import '../../css/y/y_35ybrup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bj75j-log"/><path class="fdqwsub7z"/><path class="w58xql4qz"/><path class="y_35ybrup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wood-pole-20" /></template>
