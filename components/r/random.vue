<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm6bjo4qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xm6bjo4qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:random" /></template>
