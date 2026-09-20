<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcbjxfbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcbjxfbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:move-resize-variant" /></template>
