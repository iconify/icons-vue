<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvbg1fz3a.css';
import '../../css/b/byjp5ys0b.css';
import '../../css/b/b5czk55zq.css';
import '../../css/g/g8tbddctr.css';
import '../../css/u/udxa4tbiz.css';
import '../../css/l/l8dv9b57m.css';
import '../../css/a/a4ny98emw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="hvbg1fz3a"/><path class="byjp5ys0b"/><g class="b5czk55zq"><path class="g8tbddctr"/><circle class="udxa4tbiz"/><path class="l8dv9b57m"/><path class="a4ny98emw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:transmission" /></template>
