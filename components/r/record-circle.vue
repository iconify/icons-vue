<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2d_h3bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2d_h3bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:record-circle" /></template>
