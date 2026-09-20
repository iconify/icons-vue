<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtymrw8dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rtymrw8dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:noton-dark" /></template>
