<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbsrszbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbsrszbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warm-up-2-line" /></template>
