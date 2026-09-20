<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3h1a6bcc.css';
import '../../css/y/yuyfg5bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGuIBCwefD" viewBox="0 0 72 168"><circle class="e3h1a6bcc"/><path class="yuyfg5bdi"/></symbol></defs><use width="72" height="168" href="#SVGuIBCwefD" transform="translate(220 204)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-mercury-cold" /></template>
