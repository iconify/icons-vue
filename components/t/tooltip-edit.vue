<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0w5fjbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0w5fjbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-edit" /></template>
