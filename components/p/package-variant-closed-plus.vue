<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yawa8zbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yawa8zbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-variant-closed-plus" /></template>
