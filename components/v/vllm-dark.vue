<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh8ll8kmn.css';
import '../../css/w/wgujkib2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fh8ll8kmn"/><path class="wgujkib2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vllm-dark" /></template>
