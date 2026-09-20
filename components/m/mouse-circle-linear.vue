<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nr28dlb2d.css';
import '../../css/f/f6a82rrqn.css';
import '../../css/b/b6enbdbml.css';
import '../../css/q/qq_vvgblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nr28dlb2d"/><path class="f6a82rrqn"/><path class="b6enbdbml"/><path class="qq_vvgblc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mouse-circle-linear" /></template>
