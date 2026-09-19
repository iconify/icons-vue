<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sh_k0kbjl.css';
import '../../css/t/t27kzjtxh.css';
import '../../css/f/fl3lhjceg.css';
import '../../css/e/e303g4b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="sh_k0kbjl"/><path class="t27kzjtxh"/><path class="fl3lhjceg"/><path class="e303g4b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mail" /></template>
