<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx-tguzcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx-tguzcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-3d" /></template>
