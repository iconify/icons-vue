<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o9z1up3bw.css';
import '../../css/m/m88ceybjj.css';
import '../../css/c/cg9kg7iup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o9z1up3bw"/><path class="m88ceybjj"/><path class="cg9kg7iup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:setting-done-02" /></template>
