<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/caqnx5y4d.css';
import '../../css/t/t5efulchj.css';
import '../../css/r/rh5gwkc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="caqnx5y4d"/><path class="t5efulchj"/><path class="rh5gwkc7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-receive-circle" /></template>
