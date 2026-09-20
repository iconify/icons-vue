<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v6xozwwqt.css';
import '../../css/h/hb6t3lb4p.css';
import '../../css/r/r9eucsbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v6xozwwqt"/><path class="hb6t3lb4p"/><path class="r9eucsbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-3-broken" /></template>
