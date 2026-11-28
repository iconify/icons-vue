<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3hp9nbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3hp9nbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:oven-solid" /></template>
