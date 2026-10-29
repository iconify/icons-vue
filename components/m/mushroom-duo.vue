<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wgcstei8u.css';
import '../../css/t/tsi5nvbml.css';
import '../../css/i/iycs7wjzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wgcstei8u"/><path class="tsi5nvbml wm-a"/><path class="iycs7wjzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mushroom-duo" /></template>
