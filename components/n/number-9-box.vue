<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxf2z2snj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxf2z2snj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-9-box" /></template>
