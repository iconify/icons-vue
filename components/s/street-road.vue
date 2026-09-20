<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv_0x6b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uv_0x6b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:street-road" /></template>
