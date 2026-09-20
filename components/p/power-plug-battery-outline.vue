<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9q_pobia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9q_pobia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-plug-battery-outline" /></template>
