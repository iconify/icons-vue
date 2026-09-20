<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4y2qbvi.css';
import '../../css/v/vl-s6tbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt4y2qbvi"/><path class="vl-s6tbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openhab" /></template>
