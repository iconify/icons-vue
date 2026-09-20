<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8dyc1zhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="w8dyc1zhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:scale-extend" /></template>
