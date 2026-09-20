<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4n0chxiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4n0chxiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:plug-3-line" /></template>
