<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4l5ieyvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4l5ieyvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:plane-clock" /></template>
