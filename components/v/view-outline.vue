<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2p-8wbtt.css';
import '../../css/k/kujpmsktd.css';
import '../../css/h/h0ghu0bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="w2p-8wbtt"><path class="kujpmsktd"/><path class="h0ghu0bkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:view-outline" /></template>
