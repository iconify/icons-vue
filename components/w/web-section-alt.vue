<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoojuxfxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoojuxfxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:web-section-alt" /></template>
