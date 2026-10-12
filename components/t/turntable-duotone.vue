<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xabjk5bgz.css';
import '../../css/q/q050sk4js.css';
import '../../css/n/ncstsjbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xabjk5bgz"/><path class="q050sk4js"/><path class="ncstsjbou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:turntable-duotone" /></template>
