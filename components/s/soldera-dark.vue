<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5np-7oxh.css';
import '../../css/w/wousxhbxy.css';
import '../../css/g/gzag1fbky.css';
import '../../css/r/r08d7pb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":319};
const content = `<path class="h5np-7oxh"/><path class="wousxhbxy"/><path class="gzag1fbky"/><path class="r08d7pb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:soldera-dark" /></template>
