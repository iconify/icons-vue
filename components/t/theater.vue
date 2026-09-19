<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/r/ra73nz3sb.css';
import '../../css/g/g59ctu1kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path clip-rule="evenodd" class="ra73nz3sb"/><path class="g59ctu1kl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:theater" /></template>
