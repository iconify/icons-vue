<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hjzzbm_-c.css';
import '../../css/q/qkhdtfr9w.css';
import '../../css/t/tunx47bhw.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="hjzzbm_-c"/><path clip-rule="evenodd" class="qkhdtfr9w"/><path class="tunx47bhw"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:stars-circle-filled" /></template>
