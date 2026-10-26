<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xve8_cc1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xve8_cc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:microsoft-copilot-legacy" /></template>
