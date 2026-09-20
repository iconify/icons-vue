<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u32o3n5de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u32o3n5de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vortex-logo-1" /></template>
