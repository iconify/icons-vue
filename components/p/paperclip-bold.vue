<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhh2ycz5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="nhh2ycz5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:paperclip-bold" /></template>
