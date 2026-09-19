<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/s/si5gp2b7i.css';
import '../../css/d/dx1bpub0v.css';
import '../../css/u/umf41ybqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="si5gp2b7i"/><path class="dx1bpub0v"/><path class="umf41ybqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:receiver" /></template>
