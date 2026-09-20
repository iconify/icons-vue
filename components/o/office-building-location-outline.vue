<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq5t6u07g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq5t6u07g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:office-building-location-outline" /></template>
