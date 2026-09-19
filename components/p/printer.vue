<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/si_h8nlvt.css';
import '../../css/i/i817x4i-m.css';
import '../../css/b/bt2vhjbuk.css';
import '../../css/e/e6sihfv7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="si_h8nlvt"/><path class="i817x4i-m"/><path class="bt2vhjbuk"/><path class="e6sihfv7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:printer" /></template>
