<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_2vdmzzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g_2vdmzzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:snapchat-square" /></template>
