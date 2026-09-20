<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_159j0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1534,"height":1536};
const content = `<path class="pv_159j0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-direction-sw" /></template>
