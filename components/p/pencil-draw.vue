<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl37b7c_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl37b7c_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-draw" /></template>
