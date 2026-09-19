<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulz2_jrvn.css';
import '../../css/l/lkzr4lbat.css';
import '../../css/j/jt2wz2wem.css';
import '../../css/p/peock8bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ulz2_jrvn"/><path class="lkzr4lbat"/><path class="jt2wz2wem"/><path class="peock8bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:statueofliberty" /></template>
