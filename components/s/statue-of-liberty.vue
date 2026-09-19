<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wbb0aac8o.css';
import '../../css/b/b2suoikth.css';
import '../../css/j/jxdwdmb3k.css';
import '../../css/d/dkin9ricg.css';
import '../../css/o/oz5i6ohli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wbb0aac8o"/><path class="b2suoikth"/><path class="jxdwdmb3k"/><path class="dkin9ricg"/><path class="oz5i6ohli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:statue-of-liberty" /></template>
