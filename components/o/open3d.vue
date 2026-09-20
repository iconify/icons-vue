<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch_f8mbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch_f8mbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open3d" /></template>
