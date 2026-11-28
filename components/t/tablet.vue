<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nja9a3b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nja9a3b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tablet" /></template>
