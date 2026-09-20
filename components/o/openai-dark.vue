<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0iidabjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":260};
const content = `<path class="y0iidabjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openai-dark" /></template>
