<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sspndwbmb.css';
import '../../css/v/v3bumgb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sspndwbmb"/><path class="v3bumgb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:real-debrid-dark" /></template>
