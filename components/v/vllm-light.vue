<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9nw32blw.css';
import '../../css/m/m2a5m1fuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w9nw32blw"/><path class="m2a5m1fuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vllm-light" /></template>
