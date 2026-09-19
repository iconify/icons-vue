<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp5sfuo3e.css';
import '../../css/q/qcv-ztbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jp5sfuo3e"/><path class="qcv-ztbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:share-google" /></template>
