<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgpy0vwps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wgpy0vwps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:not-equal" /></template>
