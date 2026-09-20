<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3iboo12o.css';
import '../../css/n/n0ta28bqr.css';
import '../../css/k/k45m38b3b.css';
import '../../css/z/za00otbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3iboo12o"/><path class="n0ta28bqr"/><path class="k45m38b3b"/><path class="za00otbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:react" /></template>
