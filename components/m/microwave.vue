<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/l-abkm5vc.css';
import '../../css/l/lrpts-39x.css';
import '../../css/g/gzp-pnbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="l-abkm5vc"/><path class="lrpts-39x"/><path class="gzp-pnbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:microwave" /></template>
