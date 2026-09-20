<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze5amdbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze5amdbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:resistor-nodes" /></template>
