<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy8--92xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy8--92xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:thumb-down-line" /></template>
