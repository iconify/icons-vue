<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/phsmk7b-g.css';
import '../../css/n/n-_-ghbzs.css';
import '../../css/p/ph4irppsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="phsmk7b-g"/><path class="n-_-ghbzs"/><path class="ph4irppsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-cross-pen-line-duotone" /></template>
