<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpn96qbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vpn96qbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:raster-lower-left" /></template>
