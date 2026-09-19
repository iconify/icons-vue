<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/otvcnlb6x.css';
import '../../css/k/k_zcsk45o.css';
import '../../css/o/oad6xcb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="otvcnlb6x"/><path class="k_zcsk45o"/><path class="oad6xcb_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:nutrition" /></template>
