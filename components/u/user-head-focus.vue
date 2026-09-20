<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8p7pxrlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8p7pxrlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-head-focus" /></template>
