<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvocr7pig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvocr7pig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-groups-dark" /></template>
