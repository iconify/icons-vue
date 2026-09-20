<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psvnx_b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="psvnx_b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:vercel-logo" /></template>
