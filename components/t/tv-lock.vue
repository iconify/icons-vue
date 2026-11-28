<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_cvfbjih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_cvfbjih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tv-lock" /></template>
