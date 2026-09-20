<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4u1a1xct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4u1a1xct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:multi-image-fill" /></template>
