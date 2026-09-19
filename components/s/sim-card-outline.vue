<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gq8lmn-fl.css';
import '../../css/w/w4k4oubkq.css';
import '../../css/e/eitjcwufr.css';
import '../../css/o/on3a9747h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gq8lmn-fl"/><path class="w4k4oubkq"/><path class="eitjcwufr"/><path class="on3a9747h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sim-card-outline" /></template>
