<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/camt8iiuh.css';
import '../../css/t/t915txqbu.css';
import '../../css/r/rev4qf8jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="camt8iiuh"/><path class="t915txqbu"/><path class="rev4qf8jr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mouse-22" /></template>
