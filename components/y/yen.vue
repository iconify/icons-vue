<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqqcj4exr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqqcj4exr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:yen" /></template>
