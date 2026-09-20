<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8853cbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8853cbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:volume-plus" /></template>
