<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4shc1bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4shc1bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-3-fill" /></template>
