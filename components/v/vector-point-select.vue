<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg1g93b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg1g93b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-point-select" /></template>
