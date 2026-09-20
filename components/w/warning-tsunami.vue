<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh22lt3gh.css';
import '../../css/k/ks82cb6hj.css';
import '../../css/q/qk-rao-nr.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/c/cz18k680z.css';
import '../../css/x/x5eid6x3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rh22lt3gh"/><path class="ks82cb6hj"/><path class="qk-rao-nr"/><g class="jn8qy4bru"><path class="cz18k680z"/><path class="x5eid6x3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:warning-tsunami" /></template>
