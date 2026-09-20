<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f-3m1zm3w.css';
import '../../css/a/aqk05ob5f.css';
import '../../css/i/iym8_abbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f-3m1zm3w"/><path class="aqk05ob5f"/><path class="iym8_abbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag2" /></template>
