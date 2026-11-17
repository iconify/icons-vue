<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxk4r1_gb.css';
import '../../css/b/bfgj_tbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxk4r1_gb"/><path class="bfgj_tbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vpn-sentinel-light" /></template>
