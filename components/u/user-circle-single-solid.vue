<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vov3w-bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vov3w-bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:user-circle-single-solid" /></template>
