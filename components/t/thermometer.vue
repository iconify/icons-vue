<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o-op5h98v.css';
import '../../css/d/d8ik5ij4p.css';
import '../../css/d/dejs93-4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="o-op5h98v"/><path class="d8ik5ij4p"/><path class="dejs93-4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:thermometer" /></template>
