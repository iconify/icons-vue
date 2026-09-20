<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/z0ttv6bhb.css';
import '../../css/h/hjux57bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path clip-rule="evenodd" class="z0ttv6bhb"/><path vector-effect="non-scaling-stroke" class="hjux57bau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:pending" /></template>
