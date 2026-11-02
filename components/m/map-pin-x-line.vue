<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-vdhkbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-vdhkbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-x-line" /></template>
