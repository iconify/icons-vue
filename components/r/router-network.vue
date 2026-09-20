<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mon9luzwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mon9luzwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:router-network" /></template>
