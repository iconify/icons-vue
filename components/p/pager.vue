<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy9do6bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jy9do6bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pager" /></template>
