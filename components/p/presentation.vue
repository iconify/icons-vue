<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb0u8i0od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb0u8i0od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:presentation" /></template>
