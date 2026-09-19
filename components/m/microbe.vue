<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qbu0j497j.css';
import '../../css/q/qd7txsbcd.css';
import '../../css/g/g7s0w3a6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qbu0j497j"/><path class="qd7txsbcd"/><path class="g7s0w3a6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:microbe" /></template>
