<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw0k10tqf.css';
import '../../css/r/rnj4lldhb.css';
import '../../css/w/w1yt_6bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aw0k10tqf"/><path class="rnj4lldhb"/><path class="w1yt_6bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-kit-20-bold" /></template>
