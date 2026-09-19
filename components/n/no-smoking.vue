<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dj67aulkh.css';
import '../../css/v/vnp1-m4if.css';
import '../../css/p/pget4blue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dj67aulkh"/><path class="vnp1-m4if"/><path class="pget4blue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:no-smoking" /></template>
