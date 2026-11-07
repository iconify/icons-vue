<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sgqej7bfm.css';
import '../../css/t/t25li13br.css';
import '../../css/b/bari53b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sgqej7bfm"/><path class="t25li13br"/><path class="bari53b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-off-line-duotone" /></template>
