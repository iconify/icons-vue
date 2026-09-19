<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/uzj4pbz7k.css';
import '../../css/f/fjdu8ejaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<g class="h01tyzbfu"><path transform="matrix(1.00396 0 0 1.01551 -3.915 995.337)" class="uzj4pbz7k"/><path transform="matrix(1.00396 0 0 1.01551 -3.915 995.337)" class="fjdu8ejaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:text-annotation" /></template>
