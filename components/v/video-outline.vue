<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms-fpgbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ms-fpgbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:video-outline" /></template>
