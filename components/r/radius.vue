<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt4x1e_6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt4x1e_6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:radius" /></template>
