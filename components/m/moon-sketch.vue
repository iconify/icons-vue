<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q471_irwr.css';
import '../../css/n/nhv4ufbsv.css';
import '../../css/a/a762wedry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q471_irwr"/><path class="nhv4ufbsv"/><path class="a762wedry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:moon-sketch" /></template>
