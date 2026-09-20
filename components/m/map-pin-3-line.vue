<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc_22wbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc_22wbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-3-line" /></template>
