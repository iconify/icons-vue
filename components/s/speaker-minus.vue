<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxrtblbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxrtblbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:speaker-minus" /></template>
