<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td6u0lbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="td6u0lbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:surprised-face-in-circle" /></template>
