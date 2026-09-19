<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwz5aj3dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hwz5aj3dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:puzzle-piece" /></template>
