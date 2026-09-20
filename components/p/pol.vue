<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf-e5obfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-e5obfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pol" /></template>
