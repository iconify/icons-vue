<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue1ltq7mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ue1ltq7mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:v" /></template>
