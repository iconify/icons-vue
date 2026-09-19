<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qls5yob2g.css';
import '../../css/q/qlh9ednwc.css';
import '../../css/c/c32gzu5bn.css';
import '../../css/b/bsgsx4b-b.css';
import '../../css/p/p_03qcbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qls5yob2g"/><path class="qlh9ednwc"/><path class="c32gzu5bn"/><path class="bsgsx4b-b"/><path class="p_03qcbda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:nine-thirty" /></template>
