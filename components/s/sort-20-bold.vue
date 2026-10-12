<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqm6o8bjf.css';
import '../../css/r/rtz_uvbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qqm6o8bjf"/><path class="rtz_uvbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-20-bold" /></template>
