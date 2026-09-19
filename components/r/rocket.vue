<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ixkuiac2o.css';
import '../../css/l/lez6mrb8y.css';
import '../../css/n/nmtfkrd1j.css';
import '../../css/q/qqx1kbb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ixkuiac2o"/><path clip-rule="evenodd" class="lez6mrb8y"/><path clip-rule="evenodd" class="nmtfkrd1j"/><path class="qqx1kbb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:rocket" /></template>
