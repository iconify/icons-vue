<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iue1-vgbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iue1-vgbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ruler-square-compass" /></template>
