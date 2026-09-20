<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk0epachj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jk0epachj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-anchor" /></template>
