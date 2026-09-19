<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vr7_k0dyh.css';
import '../../css/r/rs0ntdh1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vr7_k0dyh"/><path class="rs0ntdh1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-santizer-alt" /></template>
