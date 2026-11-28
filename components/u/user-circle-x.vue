<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es2oy3b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es2oy3b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-circle-x" /></template>
