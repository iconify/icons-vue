<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fatg9ib1l.css';
import '../../css/e/ei72e1ltq.css';
import '../../css/u/u37866ghy.css';
import '../../css/k/kwfvx1__p.css';
import '../../css/b/b6mu38bbk.css';
import '../../css/j/jlytocbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fatg9ib1l"/><path class="ei72e1ltq"/><circle class="u37866ghy"/><g class="kwfvx1__p"><circle class="b6mu38bbk"/><path class="jlytocbyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:reading-ebook" /></template>
