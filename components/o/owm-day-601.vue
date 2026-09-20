<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5512bc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="m5512bc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-601" /></template>
