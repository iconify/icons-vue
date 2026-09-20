<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqdnidbra.css';
import '../../css/p/ps2d02mlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqdnidbra"/><path class="ps2d02mlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:threadfin-dark" /></template>
