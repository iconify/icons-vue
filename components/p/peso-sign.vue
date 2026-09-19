<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fff_zr3dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="fff_zr3dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:peso-sign" /></template>
