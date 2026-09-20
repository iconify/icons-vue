<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7aoxobjl.css';
import '../../css/e/e2_v2hb1h.css';
import '../../css/l/lggd7ul4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="o7aoxobjl"/><path class="e2_v2hb1h"/><path class="lggd7ul4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mausoleum-at-halicarnassus" /></template>
