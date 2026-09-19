<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq-nchcxv.css';
import '../../css/d/dlp7nstpk.css';
import '../../css/q/qe3jhfb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mq-nchcxv"/><circle class="dlp7nstpk"/><path class="qe3jhfb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:object-storage" /></template>
