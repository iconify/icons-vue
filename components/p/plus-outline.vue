<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/o/ojh9awbdp.css';
import '../../css/t/t3q1ykbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="plus-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="ojh9awbdp"/><path class="t3q1ykbbo"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:plus-outline" /></template>
