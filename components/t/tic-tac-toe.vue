<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h67270lqc.css';
import '../../css/y/ybufkabpo.css';
import '../../css/a/asbceibyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h67270lqc"/><circle class="ybufkabpo"/><circle class="asbceibyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tic-tac-toe" /></template>
