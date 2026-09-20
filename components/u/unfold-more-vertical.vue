<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv0rdoajs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv0rdoajs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unfold-more-vertical" /></template>
