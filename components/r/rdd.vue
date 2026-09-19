<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wei_cibse.css';
import '../../css/b/b3o1m5bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="wei_cibse"/><path class="b3o1m5bbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rdd" /></template>
