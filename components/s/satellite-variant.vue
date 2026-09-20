<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld890q03z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld890q03z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:satellite-variant" /></template>
