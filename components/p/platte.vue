<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/q/ql2oftrja.css';
import '../../css/n/n75x16bgq.css';
import '../../css/j/j5l0kbiuf.css';
import '../../css/e/ejyqcr5od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="ql2oftrja"/><path class="n75x16bgq"/><path class="j5l0kbiuf"/><path class="ejyqcr5od"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:platte" /></template>
