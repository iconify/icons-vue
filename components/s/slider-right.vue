<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soiqe4ggu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="soiqe4ggu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:slider-right" /></template>
