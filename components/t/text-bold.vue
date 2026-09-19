<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6g817zjy.css';
import '../../css/k/k3nn7hxsv.css';
import '../../css/y/yto2jk_qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="o6g817zjy"><path class="k3nn7hxsv"/><path class="yto2jk_qy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:text-bold" /></template>
