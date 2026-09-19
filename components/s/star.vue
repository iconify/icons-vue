<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn_z0tbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn_z0tbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:star" /></template>
