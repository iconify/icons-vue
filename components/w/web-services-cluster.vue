<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arbh2nbmk.css';
import '../../css/t/tz_5mvbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="arbh2nbmk"/><path class="tz_5mvbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:web-services-cluster" /></template>
