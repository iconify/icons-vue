<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j6hlmh-yv.css';
import '../../css/b/bxpvs5bwt.css';
import '../../css/y/ylpji7cqa.css';
import '../../css/m/m-r32nl1u.css';
import '../../css/o/o54ffy1qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j6hlmh-yv"/><path class="bxpvs5bwt"/><rect class="ylpji7cqa"/><rect class="m-r32nl1u"/><path clip-rule="evenodd" class="o54ffy1qd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:note-medical" /></template>
