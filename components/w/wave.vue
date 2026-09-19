<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a75zxoc1y.css';
import '../../css/k/ke9xms0bs.css';
import '../../css/o/ozu0o6bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="a75zxoc1y"/><path class="ke9xms0bs"/><path class="ozu0o6bgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:wave" /></template>
