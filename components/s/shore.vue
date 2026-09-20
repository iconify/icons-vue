<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyz_f1bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyz_f1bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shore" /></template>
