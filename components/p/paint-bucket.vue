<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n65i2cfkw.css';
import '../../css/c/c9mwe-beg.css';
import '../../css/y/yeh6x5bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="n65i2cfkw"/><path class="c9mwe-beg wm-a"/><path class="wm-s yeh6x5bvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paint-bucket" /></template>
