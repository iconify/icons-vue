<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpiteb51d.css';
import '../../css/v/v23tyc59y.css';
import '../../css/b/bfox5ubnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qpiteb51d"/><circle class="v23tyc59y"/><path class="bfox5ubnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tour" /></template>
