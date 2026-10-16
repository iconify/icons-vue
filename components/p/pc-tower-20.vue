<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb6fqqb0z.css';
import '../../css/u/u8f88948k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jb6fqqb0z"/><path class="u8f88948k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pc-tower-20" /></template>
