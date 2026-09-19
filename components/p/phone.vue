<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/ujed1zb_y.css';
import '../../css/w/wwxsycqox.css';
import '../../css/o/os5lo5ptn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="ujed1zb_y"/><path class="wwxsycqox"/><path class="os5lo5ptn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:phone" /></template>
