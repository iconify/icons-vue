<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi466ubef.css';
import '../../css/s/sf5m5dbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wi466ubef"/><path class="sf5m5dbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:verdaccio-dark" /></template>
