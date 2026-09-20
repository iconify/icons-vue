<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krnj30b0h.css';
import '../../css/w/w2y0uhb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="krnj30b0h"/><path class="w2y0uhb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qd-dark" /></template>
