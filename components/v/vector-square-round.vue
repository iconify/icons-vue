<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbeskxbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbeskxbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vector-square-round" /></template>
