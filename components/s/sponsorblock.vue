<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m501iv-7c.css';
import '../../css/d/ddz586lyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m501iv-7c"/><path class="ddz586lyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sponsorblock" /></template>
