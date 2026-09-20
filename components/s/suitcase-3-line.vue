<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhr3rnc_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhr3rnc_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:suitcase-3-line" /></template>
