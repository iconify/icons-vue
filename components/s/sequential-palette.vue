<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg2jj14us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wg2jj14us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sequential-palette" /></template>
