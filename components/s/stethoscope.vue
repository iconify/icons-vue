<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1be_gbmb.css';
import '../../css/u/u-j5qhx3m.css';
import '../../css/o/oa6ouwivw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="n1be_gbmb"/><path class="u-j5qhx3m"/><path class="oa6ouwivw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:stethoscope" /></template>
