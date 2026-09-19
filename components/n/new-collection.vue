<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h-i3pxekm.css';
import '../../css/a/azfc0wb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="h-i3pxekm"/><path class="azfc0wb0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:new-collection" /></template>
