<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r9xy-7bxh.css';
import '../../css/c/c9y4ot_gj.css';
import '../../css/t/t62270obu.css';
import '../../css/m/mimhi5bxh.css';
import '../../css/p/p16f6bcmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="r9xy-7bxh"/><path class="c9y4ot_gj"/><path class="t62270obu"/><path class="mimhi5bxh"/><path class="p16f6bcmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:potted-plant" /></template>
