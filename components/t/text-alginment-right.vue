<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5vx6_pxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t5vx6_pxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:text-alginment-right" /></template>
