<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2b_z-b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k2b_z-b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mantelpiece-clock" /></template>
