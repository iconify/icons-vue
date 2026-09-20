<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af9r2o3oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af9r2o3oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tick-network" /></template>
