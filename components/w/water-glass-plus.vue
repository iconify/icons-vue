<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owtjlwbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owtjlwbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:water-glass-plus" /></template>
