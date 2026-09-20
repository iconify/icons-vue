<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s7m10y-tu.css';
import '../../css/l/ls11zrbpz.css';
import '../../css/j/jmw85sbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s7m10y-tu"/><path class="ls11zrbpz"/><path class="jmw85sbjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sun-fog" /></template>
