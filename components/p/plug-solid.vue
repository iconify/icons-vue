<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5gsjlbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5gsjlbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:plug-solid" /></template>
