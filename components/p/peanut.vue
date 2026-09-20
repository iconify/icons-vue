<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmxbyf.css';
import '../../css/g/g-quyv.css';
import '../../css/h/h4ibws.css';
import '../../css/q/qmaqso.css';
import '../../css/e/e65c9b.css';
import '../../css/o/oaychk.css';
import '../../css/s/so-from-56.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-1px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmxbyf"/><circle class="g-quyv h4ibws"/><circle class="g-quyv qmaqso"/><circle class="e65c9b g-quyv"/><circle class="g-quyv oaychk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:peanut" /></template>
