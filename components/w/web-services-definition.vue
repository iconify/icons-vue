<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bieq96bfh.css';
import '../../css/i/iyk4v5bbj.css';
import '../../css/t/tz_5mvbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bieq96bfh"/><path class="iyk4v5bbj"/><path class="tz_5mvbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:web-services-definition" /></template>
