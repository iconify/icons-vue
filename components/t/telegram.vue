<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f16uycbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f16uycbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:telegram" /></template>
