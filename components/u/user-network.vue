<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg485ibrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg485ibrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-network" /></template>
