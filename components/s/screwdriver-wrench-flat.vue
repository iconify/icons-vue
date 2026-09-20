<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tm1lnyblt.css';
import '../../css/z/zydpfe68l.css';
import '../../css/w/wzyv2vb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="tm1lnyblt"/><path class="zydpfe68l"/><path class="wzyv2vb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:screwdriver-wrench-flat" /></template>
