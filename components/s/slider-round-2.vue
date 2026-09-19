<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxjmq8b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nxjmq8b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:slider-round-2" /></template>
