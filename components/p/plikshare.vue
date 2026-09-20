<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moh21tptg.css';
import '../../css/o/o72bh4q6z.css';
import '../../css/c/c5142wicy.css';
import '../../css/x/x0isxmtro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="moh21tptg"/><path class="o72bh4q6z"/><path clip-rule="evenodd" class="c5142wicy"/><path class="x0isxmtro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plikshare" /></template>
