<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awd9u4bgp.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dd1x26btx.css';
import '../../css/c/cfkicbk9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awd9u4bgp secondary"/><g class="dt0cm9dhy primary"><path class="dd1x26btx"/><path class="cfkicbk9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phi-duo" /></template>
