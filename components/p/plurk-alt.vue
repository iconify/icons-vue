<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/yi_ml2bts.css';
import '../../css/f/frw1ezbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="yi_ml2bts"/><path class="frw1ezbng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:plurk-alt" /></template>
