<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzwgnzb9h.css';
import '../../css/k/k-khy6r6b.css';
import '../../css/z/z04drlb1l.css';
import '../../css/q/qw2l4vbgr.css';
import '../../css/u/uuqfk7b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="fzwgnzb9h"/><path class="k-khy6r6b"/><g class="z04drlb1l"><path class="qw2l4vbgr"/><path class="uuqfk7b7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:power-symbol" /></template>
