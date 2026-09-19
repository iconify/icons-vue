<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q9nmxacxq.css';
import '../../css/a/ay4fyksgr.css';
import '../../css/u/ug5hi9q-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="q9nmxacxq"/><path class="ay4fyksgr"/><path class="ug5hi9q-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tags-duo" /></template>
