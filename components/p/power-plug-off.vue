<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvdp7_lgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvdp7_lgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-plug-off" /></template>
