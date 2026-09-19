<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vx5xd6byq.css';
import '../../css/q/qe5mrybjn.css';
import '../../css/j/j9yh9hwkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vx5xd6byq"/><path class="qe5mrybjn"/><path class="j9yh9hwkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:studio-light-front" /></template>
