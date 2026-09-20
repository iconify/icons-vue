<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx7milbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx7milbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-polyline-edit" /></template>
