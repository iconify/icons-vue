<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq50g6kro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq50g6kro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:owl-heart" /></template>
