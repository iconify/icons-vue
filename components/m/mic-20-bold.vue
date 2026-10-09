<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uih-zwlau.css';
import '../../css/p/pc3rltyei.css';
import '../../css/r/rltagccoa.css';
import '../../css/a/an84ox-sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uih-zwlau"/><path class="pc3rltyei"/><path class="rltagccoa"/><path class="an84ox-sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mic-20-bold" /></template>
