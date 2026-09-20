<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnep6zbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="rnep6zbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:user-square" /></template>
