<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/k14x9ow3b.css';
import '../../css/l/l5c66b_ve.css';
import '../../css/q/qtt1u12ec.css';
import '../../css/g/g07kgbb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="k14x9ow3b"/><path class="l5c66b_ve"/><path class="qtt1u12ec"/><path class="g07kgbb_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:medicine-bottle-one" /></template>
