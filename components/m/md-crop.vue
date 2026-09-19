<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkfb23hos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qkfb23hos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-crop" /></template>
