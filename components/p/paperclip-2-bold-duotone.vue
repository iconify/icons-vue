<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb1rgbcrq.css';
import '../../css/r/rihb8_rrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yb1rgbcrq"/><path class="rihb8_rrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paperclip-2-bold-duotone" /></template>
