<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv5yd5ixf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv5yd5ixf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pinwheel" /></template>
