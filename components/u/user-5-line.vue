<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8q0_-tir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8q0_-tir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-5-line" /></template>
