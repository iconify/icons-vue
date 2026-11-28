<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1a2dm2xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1a2dm2xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:vinyl-play" /></template>
