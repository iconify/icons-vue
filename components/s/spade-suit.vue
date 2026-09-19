<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv-h0ub1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iv-h0ub1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:spade-suit" /></template>
