<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtb1766zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtb1766zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:visible" /></template>
