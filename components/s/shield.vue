<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtdbs_u4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vtdbs_u4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:shield" /></template>
