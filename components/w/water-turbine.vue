<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpy3xnbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpy3xnbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:water-turbine" /></template>
