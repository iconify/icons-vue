<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/esaz-g1-g.css';
import '../../css/n/nzmqz3bvt.css';
import '../../css/n/nk9jicc4w.css';
import '../../css/c/cqg5ru5ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="esaz-g1-g"/><path class="nzmqz3bvt"/><path class="nk9jicc4w"/><path class="cqg5ru5ax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-speaker-linear" /></template>
