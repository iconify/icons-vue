<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3wl0cc2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m3wl0cc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:satellite" /></template>
