<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_glx4ama.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_glx4ama"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-delivered" /></template>
