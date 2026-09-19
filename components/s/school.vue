<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhdtd5bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mhdtd5bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:school" /></template>
