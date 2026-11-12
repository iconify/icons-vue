<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsmli1cfn.css';
import '../../css/x/xfegddcoa.css';
import '../../css/u/u5r3t04hl.css';
import '../../css/b/berg0zbjr.css';
import '../../css/f/f49rs-fos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="nsmli1cfn"/><path class="xfegddcoa"/><path class="u5r3t04hl"/><path class="berg0zbjr"/><path class="f49rs-fos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tiny-tiny-rss" /></template>
