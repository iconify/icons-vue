<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh-c79jpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh-c79jpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pi-box" /></template>
