<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cj6bbpb_o.css';
import '../../css/a/aw74w_bdz.css';
import '../../css/g/giqk6m29x.css';
import '../../css/r/rce7lrwge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cj6bbpb_o"/><path class="aw74w_bdz"/><path class="giqk6m29x"/><path class="rce7lrwge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:page-facing-up" /></template>
