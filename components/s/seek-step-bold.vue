<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/o/o0n3p_e0w.css';
import '../../css/m/mzu1w-bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="to-5kdesz"><path class="o0n3p_e0w"/><path class="mzu1w-bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seek-step-bold" /></template>
