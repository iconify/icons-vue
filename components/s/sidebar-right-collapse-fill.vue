<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-bor7bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-bor7bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-right-collapse-fill" /></template>
