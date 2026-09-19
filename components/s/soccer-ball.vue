<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_iq0dnaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d_iq0dnaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:soccer-ball" /></template>
