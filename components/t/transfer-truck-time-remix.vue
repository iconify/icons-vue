<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkh6_1xxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jkh6_1xxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:transfer-truck-time-remix" /></template>
