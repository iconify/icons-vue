<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr44mmb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr44mmb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowboarding-line" /></template>
