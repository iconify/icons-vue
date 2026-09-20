<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw4lbb9iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw4lbb9iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-3d-nozzle-off-outline" /></template>
