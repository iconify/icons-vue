<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cxb5acbfq.css';
import '../../css/p/pu--7xbjp.css';
import '../../css/c/c7s0occxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cxb5acbfq"/><path class="pu--7xbjp"/><path class="c7s0occxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:suitcase-rolling-flat" /></template>
