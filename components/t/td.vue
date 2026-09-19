<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/j0uptwbwv.css';
import '../../css/p/pu5v9vwih.css';
import '../../css/c/cyr97l9zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="j0uptwbwv"/><path class="pu5v9vwih"/><path class="cyr97l9zo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:td" /></template>
