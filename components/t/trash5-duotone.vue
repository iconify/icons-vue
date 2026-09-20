<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/deu_htz4g.css';
import '../../css/a/at1ai5bbb.css';
import '../../css/s/su39-7f4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="deu_htz4g"/><path clip-rule="evenodd" class="at1ai5bbb"/><path class="su39-7f4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash5-duotone" /></template>
