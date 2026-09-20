<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn9z0ybli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn9z0ybli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-pause-outline" /></template>
