<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/p/p1xl0obnf.css';
import '../../css/r/r_-y31b5j.css';
import '../../css/e/eac117bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="p1xl0obnf"/><path class="r_-y31b5j"/><path class="eac117bae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-sum" /></template>
