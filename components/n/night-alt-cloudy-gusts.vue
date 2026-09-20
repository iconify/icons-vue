<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjtkvdbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="qjtkvdbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-cloudy-gusts" /></template>
