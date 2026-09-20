<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9blw_16z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9blw_16z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tsdproxy-light" /></template>
