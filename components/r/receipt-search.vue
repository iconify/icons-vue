<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd26umbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd26umbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:receipt-search" /></template>
