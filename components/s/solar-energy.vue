<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnb6oiblm.css';
import '../../css/r/rreybl3mq.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/i/i-d783b6j.css';
import '../../css/w/w2kqwju0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cnb6oiblm"/><circle class="rreybl3mq"/><g class="jn8qy4bru"><path class="i-d783b6j"/><circle class="w2kqwju0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:solar-energy" /></template>
