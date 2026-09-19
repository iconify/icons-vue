<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j8wxn8xap.css';
import '../../css/a/agwzg2atf.css';
import '../../css/x/x3_kr2bze.css';
import '../../css/v/vl_70lije.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="j8wxn8xap"/><path clip-rule="evenodd" class="agwzg2atf"/><path clip-rule="evenodd" class="x3_kr2bze"/><path class="vl_70lije"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rdt-result-positive-outline" /></template>
