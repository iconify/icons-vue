<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqut5_rjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqut5_rjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paint-roller" /></template>
