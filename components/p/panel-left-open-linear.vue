<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lr78om9_g.css';
import '../../css/j/j-3yojbro.css';
import '../../css/w/wk0dhccfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lr78om9_g"/><path class="j-3yojbro"/><path class="wk0dhccfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-open-linear" /></template>
