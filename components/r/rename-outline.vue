<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwgzm4b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwgzm4b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rename-outline" /></template>
