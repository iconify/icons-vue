<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voby0cawe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voby0cawe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wide-area-network" /></template>
