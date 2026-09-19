<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwtyhia0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwtyhia0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:twitter-x" /></template>
