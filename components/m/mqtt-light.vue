<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pprnic1yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pprnic1yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mqtt-light" /></template>
