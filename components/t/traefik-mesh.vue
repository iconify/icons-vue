<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cauiu9xcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cauiu9xcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:traefik-mesh" /></template>
