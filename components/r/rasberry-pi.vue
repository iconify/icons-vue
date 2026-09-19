<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5u74dhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py5u74dhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:rasberry-pi" /></template>
