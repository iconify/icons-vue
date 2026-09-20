<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vro6cvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vro6cvbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:taxi-and-arrow-right-above-arrow-left" /></template>
