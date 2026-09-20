<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3-hvq8uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3-hvq8uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-v-filled" /></template>
