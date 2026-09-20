<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry0q1bu3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ry0q1bu3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:zoom-out" /></template>
