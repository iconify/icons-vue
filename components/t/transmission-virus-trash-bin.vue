<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxldpx7ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxldpx7ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-trash-bin" /></template>
