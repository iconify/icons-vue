<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2_atrbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="s2_atrbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-211" /></template>
