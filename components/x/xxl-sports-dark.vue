<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xld-v2bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xld-v2bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xxl-sports-dark" /></template>
