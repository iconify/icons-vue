<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/t/tdxk8fb6w.css';
import '../../css/i/i3n02bb-n.css';
import '../../css/i/i1pto1bba.css';
import '../../css/d/dcpocbbnf.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="tdxk8fb6w"/><path class="i3n02bb-n"/><path class="i1pto1bba"/><path class="dcpocbbnf"/></g><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:rewind-time-off" /></template>
