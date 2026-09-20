<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg50ktb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg50ktb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-network-outline" /></template>
