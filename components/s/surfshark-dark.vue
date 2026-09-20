<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hx8ibfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_hx8ibfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:surfshark-dark" /></template>
