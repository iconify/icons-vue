<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/eih860bef.css';
import '../../css/t/tn_ex2brk.css';
import '../../css/a/aw3-wq9gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="eih860bef"/><path class="tn_ex2brk"/><path class="aw3-wq9gf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:prawn" /></template>
