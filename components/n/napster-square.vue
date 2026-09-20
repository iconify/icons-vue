<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/or8qiobhz.css';
import '../../css/v/vwh2r0r7q.css';
import '../../css/v/v25gzjbrl.css';
import '../../css/p/pltokbbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="or8qiobhz"/><path class="vwh2r0r7q"/><path class="v25gzjbrl"/><path class="pltokbbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:napster-square" /></template>
