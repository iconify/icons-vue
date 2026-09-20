<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys2i7ybay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ys2i7ybay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:powershell-universal" /></template>
