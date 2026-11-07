<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l79lhfkzr.css';
import '../../css/h/hi_zb0bdv.css';
import '../../css/z/zy5pg_7lj.css';
import '../../css/m/mzfoi9l1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l79lhfkzr"/><path class="hi_zb0bdv"/><path class="zy5pg_7lj"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:upload-twice-square-outline" /></template>
