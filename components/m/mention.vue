<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/a/aqhok2bbj.css';
import '../../css/c/c3ctpngqm.css';
import '../../css/s/s4r7xqb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="aqhok2bbj"/><path class="c3ctpngqm"/><path class="s4r7xqb6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:mention" /></template>
