<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv1w6dbgf.css';
import '../../css/y/yglam5kqs.css';
import '../../css/v/vqeh6flxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv1w6dbgf"/><path class="yglam5kqs"/><circle class="vqeh6flxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:speaker" /></template>
