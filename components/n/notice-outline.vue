<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2htaif8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2htaif8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:notice-outline" /></template>
