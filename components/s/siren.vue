<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1s8uvbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1s8uvbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:siren" /></template>
