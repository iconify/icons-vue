<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msncihl_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="msncihl_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:qr-code" /></template>
