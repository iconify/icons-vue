<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f3w91ubqa.css';
import '../../css/j/j1-zg0xja.css';
import '../../css/t/tow7vpjog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f3w91ubqa"/><path class="j1-zg0xja"/><path class="tow7vpjog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:presentation-bar-chart-02" /></template>
