<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/u/uqz3ssidv.css';
import '../../css/g/gab0h-cqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="uqz3ssidv"/><path class="gab0h-cqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:plus" /></template>
