<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8s6xvu0y.css';
import '../../css/e/ed612wbnx.css';
import '../../css/o/o-g8_8o4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="ed612wbnx"/><path clip-rule="evenodd" class="o-g8_8o4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-query-promql" /></template>
