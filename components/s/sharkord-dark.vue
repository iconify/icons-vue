<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl117jbyi.css';
import '../../css/i/ipbgiccho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tl117jbyi"/><path class="ipbgiccho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sharkord-dark" /></template>
