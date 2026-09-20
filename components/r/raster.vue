<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-hk2hbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-hk2hbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:raster" /></template>
