<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0rewwboe.css';
import '../../css/r/rwf94xd_g.css';
import '../../css/a/axl75o_4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0rewwboe"/><path class="rwf94xd_g"/><path class="axl75o_4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:soil-moisture-global" /></template>
