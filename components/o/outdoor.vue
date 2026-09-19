<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvilx1q3c.css';
import '../../css/j/j3pc6w1hl.css';
import '../../css/e/ec7k6mp6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="j3pc6w1hl"/><path class="ec7k6mp6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:outdoor" /></template>
