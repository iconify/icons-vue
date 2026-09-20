<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p7aa-3nja.css';
import '../../css/t/tldq1_vqs.css';
import '../../css/k/kk6lmubmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="p7aa-3nja"/><path class="tldq1_vqs"/><path class="kk6lmubmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-round-line-duotone" /></template>
