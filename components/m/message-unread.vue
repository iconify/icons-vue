<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hnxm9dodq.css';
import '../../css/u/u6kli1p7b.css';
import '../../css/a/ag86xlbwr.css';
import '../../css/n/n52fv9bbx.css';
import '../../css/j/j7ps5bc2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="hnxm9dodq"/><path class="u6kli1p7b"/><path class="ag86xlbwr"/><path class="n52fv9bbx"/><circle class="j7ps5bc2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:message-unread" /></template>
