<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sla533brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sla533brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-check" /></template>
