<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-s4cclro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s-s4cclro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-pipe-return-bend-with-motor-and-handle" /></template>
