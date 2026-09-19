<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yedc29b5u.css';
import '../../css/x/xdemm2bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yedc29b5u"/><path class="xdemm2bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:power-fill" /></template>
