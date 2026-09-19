<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ged9b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="m5ged9b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seek-skip" /></template>
