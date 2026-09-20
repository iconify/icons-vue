<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e101s5r6a.css';
import '../../css/q/qcwdnbbyu.css';
import '../../css/n/n8foidhcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":720,"height":720};
const content = `<g class="ft5dv1b6b"><rect class="e101s5r6a"/><g clip-path="url(#SVGugIPLcHS)"><path class="qcwdnbbyu"/></g><defs><clipPath id="SVGugIPLcHS"><path class="n8foidhcv"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pipedrive" /></template>
