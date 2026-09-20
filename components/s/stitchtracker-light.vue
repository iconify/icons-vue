<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iou1crsje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iou1crsje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stitchtracker-light" /></template>
