<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl3pr2-vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl3pr2-vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:underline" /></template>
