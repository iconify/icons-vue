<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd3tncc0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd3tncc0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pnpm-solid" /></template>
