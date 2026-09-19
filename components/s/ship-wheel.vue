<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i64-1ebxw.css';
import '../../css/y/ysvgjxbjj.css';
import '../../css/t/tlifriksx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="i64-1ebxw"/><path class="ysvgjxbjj"/><circle class="tlifriksx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ship-wheel" /></template>
