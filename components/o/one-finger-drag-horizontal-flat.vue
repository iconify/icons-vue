<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h6rbr1bpn.css';
import '../../css/v/vc4u717fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="h6rbr1bpn"/><path clip-rule="evenodd" class="vc4u717fc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:one-finger-drag-horizontal-flat" /></template>
