<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvzmnhbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvzmnhbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zigbee" /></template>
