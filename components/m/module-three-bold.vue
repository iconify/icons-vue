<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryf61ccyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryf61ccyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:module-three-bold" /></template>
