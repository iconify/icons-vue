<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdhpu3bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdhpu3bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-star-outline" /></template>
