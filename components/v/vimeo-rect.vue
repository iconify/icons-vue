<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxoo9ox9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="fxoo9ox9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:vimeo-rect" /></template>
