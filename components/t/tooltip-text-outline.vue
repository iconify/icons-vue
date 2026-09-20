<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3ok7lntz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3ok7lntz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-text-outline" /></template>
