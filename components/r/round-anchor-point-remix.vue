<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iczeisd4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iczeisd4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:round-anchor-point-remix" /></template>
