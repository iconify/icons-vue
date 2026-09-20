<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcaca32fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcaca32fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:skillshare" /></template>
