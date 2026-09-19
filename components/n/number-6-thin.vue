<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjjbb0bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjjbb0bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6-thin" /></template>
