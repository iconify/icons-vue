<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhxz97bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxz97bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-x-sharp" /></template>
