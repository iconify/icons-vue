<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2k-epblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2k-epblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:tooltips-line" /></template>
