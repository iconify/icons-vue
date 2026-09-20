<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bk50ckbpt.css';
import '../../css/t/t3i0929hw.css';
import '../../css/g/gs7_5ebow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bk50ckbpt"/><path class="t3i0929hw"/><path class="gs7_5ebow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-angular-line-duotone" /></template>
