<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwtp78bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwtp78bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:water-heater" /></template>
