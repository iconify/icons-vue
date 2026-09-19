<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diqu0zb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":383,"height":512};
const content = `<path class="diqu0zb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:nano" /></template>
