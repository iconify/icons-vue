<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnsow-zal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnsow-zal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:tooltip-text-line" /></template>
