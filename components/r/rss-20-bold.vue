<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0oe2vbzu.css';
import '../../css/z/zijqf-s4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i0oe2vbzu"/><path class="zijqf-s4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rss-20-bold" /></template>
