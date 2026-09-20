<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv22wab9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zv22wab9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:transmission-dark" /></template>
