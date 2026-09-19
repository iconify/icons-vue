<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddhndwbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddhndwbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nebula" /></template>
