<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol9yrdunc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ol9yrdunc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valhalla-maps-light" /></template>
