<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrh6l-b4x.css';
import '../../css/r/r98wmc10g.css';
import '../../css/y/ygpkzyb7g.css';
import '../../css/c/cb3t-_oid.css';
import '../../css/q/qh_4148js.css';
import '../../css/t/t60kkwbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrh6l-b4x"/><path class="r98wmc10g"/><path class="ygpkzyb7g"/><path class="cb3t-_oid"/><path class="qh_4148js"/><path class="t60kkwbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wise" /></template>
