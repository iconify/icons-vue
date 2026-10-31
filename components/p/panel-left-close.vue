<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/laiauramu.css';
import '../../css/q/quk-34b0j.css';
import '../../css/c/cvpr-5bot.css';
import '../../css/l/l3ffq6ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="laiauramu wm-shadow"/><path class="quk-34b0j wm-shadow"/><path class="cvpr-5bot"/><path class="l3ffq6ben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:panel-left-close" /></template>
