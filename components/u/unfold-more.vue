<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cazqnib9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":384};
const content = `<path class="cazqnib9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:unfold-more" /></template>
