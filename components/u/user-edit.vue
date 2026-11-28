<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa9uk5dxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa9uk5dxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-edit" /></template>
