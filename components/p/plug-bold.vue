<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ivlp6wbtj.css';
import '../../css/p/pvubd7btq.css';
import '../../css/w/wdh8nabwl.css';
import '../../css/n/nygmwf4qf.css';
import '../../css/e/exqhuybkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ivlp6wbtj"/><path class="pvubd7btq"/><path class="wdh8nabwl"/><path clip-rule="evenodd" class="nygmwf4qf"/><path class="exqhuybkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plug-bold" /></template>
