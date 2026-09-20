<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gm08kwb2q.css';
import '../../css/o/ob790gbsh.css';
import '../../css/u/u8k-dprav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="gm08kwb2q"/><path class="ob790gbsh"/><rect class="u8k-dprav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:paint-roller" /></template>
