<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3emnbbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3emnbbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-small-round" /></template>
