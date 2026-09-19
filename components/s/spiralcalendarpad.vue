<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfonkl3tm.css';
import '../../css/f/ff9oe5f4b.css';
import '../../css/u/ud97m9_ht.css';
import '../../css/e/ejtxx9bgq.css';
import '../../css/e/echjmcczc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfonkl3tm"/><path class="ff9oe5f4b"/><path class="ud97m9_ht"/><path class="ejtxx9bgq"/><path class="echjmcczc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:spiralcalendarpad" /></template>
