<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6-w_wb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-w_wb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stove-clock" /></template>
