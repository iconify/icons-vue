<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6_xn_4i.css';
import '../../css/s/sx9el_bjm.css';
import '../../css/i/iecyqkq9h.css';
import '../../css/e/eojgc1bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="sx9el_bjm"/><path class="iecyqkq9h"/><path class="eojgc1bbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:stitches" /></template>
