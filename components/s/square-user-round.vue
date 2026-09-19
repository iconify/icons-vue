<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/ief88gblg.css';
import '../../css/d/d1xlaxbzx.css';
import '../../css/l/l00awn5kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ief88gblg"/><path class="d1xlaxbzx"/><path class="l00awn5kw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-user-round" /></template>
