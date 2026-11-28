<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1y0cxqvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1y0cxqvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paint-roller-check" /></template>
