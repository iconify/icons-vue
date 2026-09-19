<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojihu_awq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ojihu_awq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pinching-hand" /></template>
