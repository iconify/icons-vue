<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/k/k9-ief91f.css';
import '../../css/x/xe5cxnbbr.css';
import '../../css/v/vri033z6n.css';
import '../../css/h/h169u-bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="k9-ief91f"/><path clip-rule="evenodd" class="xe5cxnbbr"/></g><path clip-rule="evenodd" class="vri033z6n"/><path clip-rule="evenodd" class="h169u-bvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:water-drop-print" /></template>
