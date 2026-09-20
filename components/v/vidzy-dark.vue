<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_lrdrm-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g_lrdrm-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vidzy-dark" /></template>
