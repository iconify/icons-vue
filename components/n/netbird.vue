<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt31c58xs.css';
import '../../css/l/lwvq-ccsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yt31c58xs"/><path class="lwvq-ccsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netbird" /></template>
