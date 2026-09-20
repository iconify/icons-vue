<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_raf5bng.css';
import '../../css/c/c5kg9pbyd.css';
import '../../css/l/lmk0_abjw.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/k/k--9pjhxt.css';
import '../../css/f/fvcjk13yc.css';
import '../../css/z/z0ze7-z9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="e_raf5bng"><circle class="c5kg9pbyd"/><path class="lmk0_abjw"/></g><g class="brzn_0bpr"><circle class="k--9pjhxt"/><path class="fvcjk13yc"/><path class="z0ze7-z9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:woman-cartwheeling-dark-skin-tone" /></template>
