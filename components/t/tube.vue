<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcdsv_bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-9,"top":-2};
const content = `<path class="pcdsv_bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tube" /></template>
