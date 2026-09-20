<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy9fe6p_r.css';
import '../../css/x/xtw0f8b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gy9fe6p_r"/><path class="xtw0f8b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:transportation-helicopter" /></template>
