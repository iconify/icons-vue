<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dr3q1c4he.css';
import '../../css/j/jom5s_aeb.css';
import '../../css/s/slgej5a-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="dr3q1c4he"/><rect class="jom5s_aeb"/><path class="slgej5a-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:microphone-warning" /></template>
