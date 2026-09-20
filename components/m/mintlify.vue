<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rsgvqsbiw.css';
import '../../css/n/no17qlb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":19};
const content = `<g class="ft5dv1b6b"><path class="rsgvqsbiw"/><path class="no17qlb2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mintlify" /></template>
