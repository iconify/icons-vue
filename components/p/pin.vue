<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4kyp0igz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4kyp0igz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pin" /></template>
