<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jmv52wbro.css';
import '../../css/r/r7ipq5s-n.css';
import '../../css/a/axjtsp52f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jmv52wbro"/><path class="r7ipq5s-n"/><path class="axjtsp52f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-minimalistic-horizontal-broken" /></template>
