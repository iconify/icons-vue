<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q-88mvxik.css';
import '../../css/v/vjocsrbku.css';
import '../../css/f/fdap0sbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q-88mvxik"/><path class="vjocsrbku"/><path class="fdap0sbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:vertical-resize" /></template>
