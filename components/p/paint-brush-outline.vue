<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmebte2ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmebte2ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-outline" /></template>
