<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc9-iebck.css';
import '../../css/w/w2x3wnbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fc9-iebck"/><path class="w2x3wnbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-max" /></template>
