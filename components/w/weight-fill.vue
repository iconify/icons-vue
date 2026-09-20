<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkzmbib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xkzmbib4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:weight-fill" /></template>
