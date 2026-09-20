<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfy3eubrn.css';
import '../../css/h/hoeze_b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<ellipse class="hfy3eubrn"/><path class="hoeze_b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:snowboarding" /></template>
