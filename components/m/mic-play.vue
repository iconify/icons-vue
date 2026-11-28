<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl1w0n5jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl1w0n5jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mic-play" /></template>
