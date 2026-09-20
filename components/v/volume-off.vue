<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-265-bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u-265-bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:volume-off" /></template>
