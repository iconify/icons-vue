<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qxlgbccih.css';
import '../../css/k/k_pdj69rf.css';
import '../../css/u/ui2s02ojw.css';
import '../../css/h/hadzi1b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qxlgbccih"/><path class="k_pdj69rf"/><path class="ui2s02ojw"/><path class="hadzi1b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:st" /></template>
