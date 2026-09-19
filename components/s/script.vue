<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/befny0bst.css';
import '../../css/c/cjm1ouksc.css';
import '../../css/u/ufci-5pkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g class="befny0bst"><path class="cjm1ouksc"/><path class="ufci-5pkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:script" /></template>
