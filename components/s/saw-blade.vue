<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5byd3bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5byd3bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:saw-blade" /></template>
