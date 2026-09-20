<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe3g_bcxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe3g_bcxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playlist-add" /></template>
