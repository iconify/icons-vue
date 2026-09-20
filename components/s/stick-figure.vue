<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg5_pqm5r.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/e/eg3fyqypm.css';
import '../../css/m/mh0qc9gvl.css';
import '../../css/r/r8x_2_5yj.css';
import '../../css/m/m8195sbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tg5_pqm5r"/><g class="brzn_0bpr"><path class="eg3fyqypm"/><path class="mh0qc9gvl"/><path class="r8x_2_5yj"/><circle class="m8195sbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:stick-figure" /></template>
