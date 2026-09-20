<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5r8-vbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5r8-vbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stopwatch-alert" /></template>
