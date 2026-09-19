<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vhhn7sf4c.css';
import '../../css/j/jpe9a_1ci.css';
import '../../css/c/c2r4yob4m.css';
import '../../css/g/glza9bc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vhhn7sf4c"/><path class="jpe9a_1ci"/><path class="c2r4yob4m"/><path class="glza9bc4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:test-tube-03" /></template>
