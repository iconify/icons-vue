<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_uf0fb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="h_uf0fb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pull-left" /></template>
