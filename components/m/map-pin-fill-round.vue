<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7mm91p0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7mm91p0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-fill-round" /></template>
