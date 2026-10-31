<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1d_dd5jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1d_dd5jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-help-round" /></template>
