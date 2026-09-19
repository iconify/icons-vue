<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l9ji29bjl.css';
import '../../css/r/rvykhok8p.css';
import '../../css/z/zujlmjbyq.css';
import '../../css/i/ic93-05sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l9ji29bjl"/><path class="rvykhok8p"/><path class="zujlmjbyq"/><path class="ic93-05sp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:translate" /></template>
