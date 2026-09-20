<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/d64aytbpv.css';
import '../../css/r/rqxh9mzju.css';
import '../../css/u/ubjfz4bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="d64aytbpv"/><path class="rqxh9mzju"/><path class="ubjfz4bbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:shopping-cart-trolley-download" /></template>
