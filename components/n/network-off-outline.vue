<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjdit39oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjdit39oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-off-outline" /></template>
