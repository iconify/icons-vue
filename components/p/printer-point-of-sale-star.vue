<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-0y2lb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-0y2lb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-star" /></template>
