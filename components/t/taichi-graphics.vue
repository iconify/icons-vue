<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxf6sztqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxf6sztqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:taichi-graphics" /></template>
