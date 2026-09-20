<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg54w6bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg54w6bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:multiply-network" /></template>
