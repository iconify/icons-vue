<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k73nz6b7k.css';
import '../../css/r/r5mq_bbez.css';
import '../../css/z/zqmwupo5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="k73nz6b7k"/><path class="r5mq_bbez"/><path class="zqmwupo5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:politics-compaign-flat" /></template>
