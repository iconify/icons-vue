<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bngkp7yhv.css';
import '../../css/o/o9rdwyb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bngkp7yhv"/><path class="o9rdwyb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:windy-snow" /></template>
