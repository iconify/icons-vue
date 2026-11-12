<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk0phibge.css';
import '../../css/o/ozfgr-c4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk0phibge"/><path class="ozfgr-c4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synclyrics-dark" /></template>
