<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu3kveshj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pu3kveshj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:self-hosted-metrics-light" /></template>
