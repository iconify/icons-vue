<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzsdd8o_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yzsdd8o_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:paint-roller" /></template>
