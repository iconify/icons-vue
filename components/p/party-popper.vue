<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi_1hp_-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_1hp_-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:party-popper" /></template>
