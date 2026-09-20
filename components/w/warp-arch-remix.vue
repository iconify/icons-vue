<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tumn9_bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tumn9_bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warp-arch-remix" /></template>
