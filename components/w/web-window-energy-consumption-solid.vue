<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czc8w0x3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czc8w0x3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:web-window-energy-consumption-solid" /></template>
