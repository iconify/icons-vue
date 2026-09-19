<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp702zbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp702zbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-left-gesture" /></template>
