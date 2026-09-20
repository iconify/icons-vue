<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbq-w5j8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vbq-w5j8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:media-step-forward" /></template>
