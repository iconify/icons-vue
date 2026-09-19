<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/beqnu5b5d.css';
import '../../css/t/td2l0lh5v.css';
import '../../css/x/x036cgb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="beqnu5b5d"/><path class="td2l0lh5v"/><path class="x036cgb2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-01" /></template>
