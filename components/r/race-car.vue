<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b3qiuzyym.css';
import '../../css/k/k65e6cbzd.css';
import '../../css/m/mu9py3vhm.css';
import '../../css/f/fmqakbb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b3qiuzyym"/><path clip-rule="evenodd" class="k65e6cbzd"/><path class="mu9py3vhm"/><path class="fmqakbb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:race-car" /></template>
