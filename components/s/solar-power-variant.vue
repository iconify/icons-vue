<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqfx_u2ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqfx_u2ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solar-power-variant" /></template>
