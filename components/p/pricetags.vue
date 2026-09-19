<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lf3h5acbj.css';
import '../../css/x/xz6zk-u5v.css';
import '../../css/l/l5rx36btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lf3h5acbj"/><path class="xz6zk-u5v"/><path class="l5rx36btv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:pricetags" /></template>
