<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsl_4ebcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsl_4ebcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:star-square-filled" /></template>
