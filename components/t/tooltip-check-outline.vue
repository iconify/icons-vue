<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frzutgrtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frzutgrtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-check-outline" /></template>
