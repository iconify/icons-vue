<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdofmibhs.css';
import '../../css/t/trvimmbgr.css';
import '../../css/d/ds9su0blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rdofmibhs"/><path class="trvimmbgr"/><circle class="ds9su0blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:world-monitor-light" /></template>
