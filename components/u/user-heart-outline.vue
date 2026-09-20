<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaf_pfb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaf_pfb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-heart-outline" /></template>
