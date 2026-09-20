<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx_r_-bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fx_r_-bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:unfold" /></template>
