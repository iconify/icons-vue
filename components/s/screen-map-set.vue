<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkb7xobyc.css';
import '../../css/a/avbzggl1s.css';
import '../../css/l/l6u_258ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gkb7xobyc"/><path class="avbzggl1s"/><path class="l6u_258ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:screen-map-set" /></template>
