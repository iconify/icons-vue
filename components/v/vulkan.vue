<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0j3x4yvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0j3x4yvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vulkan" /></template>
