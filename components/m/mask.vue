<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t8hauoi6q.css';
import '../../css/i/i5_8b_byv.css';
import '../../css/p/pu0hdob-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t8hauoi6q"/><path class="i5_8b_byv"/><path class="pu0hdob-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mask" /></template>
