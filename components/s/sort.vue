<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nt1kefbbp.css';
import '../../css/q/qh81i-sch.css';
import '../../css/b/buhk06bdh.css';
import '../../css/v/vajc6qbkk.css';
import '../../css/c/cgkl-pu4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nt1kefbbp"/><path class="qh81i-sch"/><path class="buhk06bdh"/><path class="vajc6qbkk"/><path class="cgkl-pu4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:sort" /></template>
