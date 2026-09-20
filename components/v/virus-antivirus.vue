<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqax-6b-d.css';
import '../../css/p/pl_8ukb7k.css';
import '../../css/o/oh466gozg.css';
import '../../css/n/n8ly77pzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="pl_8ukb7k"/><path class="oh466gozg"/><path class="n8ly77pzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:virus-antivirus" /></template>
