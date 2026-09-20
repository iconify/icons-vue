<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/s/s-t8kdbfg.css';
import '../../css/j/j9ml2vbvl.css';
import '../../css/e/eelfzzviu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="s-t8kdbfg"/><path class="j9ml2vbvl"/><path class="eelfzzviu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:maximise" /></template>
