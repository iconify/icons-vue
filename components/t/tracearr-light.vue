<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4jpk8bpd.css';
import '../../css/r/rwmxrkntq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m4jpk8bpd"/><path class="rwmxrkntq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tracearr-light" /></template>
