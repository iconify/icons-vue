<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwns-mv1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="vwns-mv1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:network-warning" /></template>
