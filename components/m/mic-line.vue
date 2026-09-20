<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxdx7ij6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxdx7ij6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:mic-line" /></template>
