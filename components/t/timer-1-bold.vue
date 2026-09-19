<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fer6iobvf.css';
import '../../css/l/lh95obbwd.css';
import '../../css/h/hyu-j45la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fer6iobvf"/><path clip-rule="evenodd" class="lh95obbwd"/><path class="hyu-j45la"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:timer-1-bold" /></template>
