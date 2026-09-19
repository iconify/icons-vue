<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq8waybzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq8waybzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zigbee2mqtt" /></template>
