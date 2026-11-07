<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtpeb-edw.css';
import '../../css/o/o0l0yrncv.css';
import '../../css/y/yhu770tis.css';
import '../../css/t/tslomuedm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="o0l0yrncv"/><path class="yhu770tis"/></g><path class="tslomuedm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-vertical-bold-duotone" /></template>
