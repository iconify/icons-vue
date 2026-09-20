<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq16c_bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq16c_bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:yahoo-line" /></template>
