<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeu84ubtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeu84ubtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:wave-pulse-1" /></template>
