<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wp4knqb8q.css';
import '../../css/k/khnsq01cy.css';
import '../../css/i/i5xw9gqsb.css';
import '../../css/e/eaj47cc_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k wp4knqb8q"/><path class="khnsq01cy wm-a"/><path class="i5xw9gqsb wm-k"/><path class="eaj47cc_q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palm-tree-sketch" /></template>
