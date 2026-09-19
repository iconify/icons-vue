<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/ucmf90w8w.css';
import '../../css/r/rpipyf98w.css';
import '../../css/d/dks-6wcfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucmf90w8w"/><path class="rpipyf98w"/><path class="dks-6wcfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plant-03" /></template>
