<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dghkc8bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="dghkc8bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-speed-1-25x" /></template>
