<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-pcz6bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-pcz6bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:whisk" /></template>
