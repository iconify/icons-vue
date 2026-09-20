<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-nxd9b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-nxd9b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:shield" /></template>
