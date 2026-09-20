<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gos-uetpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gos-uetpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-box-multiple-outline" /></template>
