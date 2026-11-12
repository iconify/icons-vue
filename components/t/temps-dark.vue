<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntdd5ebmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ntdd5ebmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:temps-dark" /></template>
