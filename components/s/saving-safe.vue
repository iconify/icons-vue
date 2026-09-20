<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l06k46s7t.css';
import '../../css/u/uh3i7lbjn.css';
import '../../css/p/p2knvgb9s.css';
import '../../css/v/v3qpbbmct.css';
import '../../css/c/cni0gsbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l06k46s7t"/><path class="uh3i7lbjn"/><path class="p2knvgb9s"/><path class="v3qpbbmct"/><path class="cni0gsbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:saving-safe" /></template>
