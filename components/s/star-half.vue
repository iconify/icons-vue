<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upwf8cbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upwf8cbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:star-half" /></template>
