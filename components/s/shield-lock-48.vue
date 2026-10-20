<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lld64mb1j.css';
import '../../css/i/it1d66trk.css';
import '../../css/k/k57p5ac6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lld64mb1j"/><path class="it1d66trk"/><path class="k57p5ac6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-lock-48" /></template>
