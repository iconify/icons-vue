<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-d1zfbuf.css';
import '../../css/w/wa25nab9h.css';
import '../../css/c/cj64798lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-d1zfbuf"/><path class="wa25nab9h"/><path class="cj64798lz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-2-line-duotone" /></template>
