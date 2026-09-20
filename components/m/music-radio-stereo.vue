<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-bpbgly.css';
import '../../css/n/nswt9dxqv.css';
import '../../css/k/kvwx-47iv.css';
import '../../css/s/slhhf6z5k.css';
import '../../css/l/l0jbyu70v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jr-bpbgly"/><path class="nswt9dxqv"/><path class="kvwx-47iv"/><path class="slhhf6z5k"/><path class="l0jbyu70v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:music-radio-stereo" /></template>
