<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/looy1fptd.css';
import '../../css/b/bstbjibrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g transform="translate(0 947.638)"><rect class="looy1fptd"/><path class="bstbjibrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:user-task" /></template>
