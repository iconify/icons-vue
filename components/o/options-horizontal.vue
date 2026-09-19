<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2dbmfb2b.css';
import '../../css/g/guczw2b4h.css';
import '../../css/o/o43_bebxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2dbmfb2b"/><path class="guczw2b4h"/><path class="o43_bebxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:options-horizontal" /></template>
