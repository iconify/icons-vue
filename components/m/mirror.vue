<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/watrobcwe.css';
import '../../css/c/c73611bax.css';
import '../../css/i/iff8-juqi.css';
import '../../css/h/hj1c6pywy.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/g/g2aoiwb3v.css';
import '../../css/i/ikluv5b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="watrobcwe"/><path class="c73611bax"/><path class="iff8-juqi"/><path class="hj1c6pywy"/><g class="jn8qy4bru"><ellipse class="g2aoiwb3v"/><path class="ikluv5b6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:mirror" /></template>
