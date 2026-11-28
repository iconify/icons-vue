<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtt32ccdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtt32ccdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sort-asc" /></template>
