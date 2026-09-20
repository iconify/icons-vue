<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghdvi_b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghdvi_b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-marker-tick" /></template>
