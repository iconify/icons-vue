<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhnh0nrcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhnh0nrcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-wifi-line" /></template>
