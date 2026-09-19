<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hug9b6uqn.css';
import '../../css/g/g-2yoqbsw.css';
import '../../css/k/kyhrmps2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hug9b6uqn"/><path class="g-2yoqbsw"/><path class="kyhrmps2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:presentation-line-chart-01" /></template>
