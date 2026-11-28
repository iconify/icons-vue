<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rebh1z_zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rebh1z_zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-arrow-right" /></template>
