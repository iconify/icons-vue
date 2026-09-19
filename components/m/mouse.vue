<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie0u-y0-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":480};
const content = `<path class="ie0u-y0-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mouse" /></template>
