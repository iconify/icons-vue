<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnsr8kbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lnsr8kbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qdirstat-light" /></template>
