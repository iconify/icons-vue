<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkdap9pwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkdap9pwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-tower-line" /></template>
