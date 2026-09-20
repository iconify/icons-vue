<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw9r1w66o.css';
import '../../css/k/kvq9f4byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw9r1w66o"/><path class="kvq9f4byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:purse" /></template>
