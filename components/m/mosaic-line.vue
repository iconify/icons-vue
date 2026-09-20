<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fznaw2yrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fznaw2yrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mosaic-line" /></template>
