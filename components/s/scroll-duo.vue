<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afdj8ubap.css';
import '../../css/i/i_eawsnbu.css';
import '../../css/r/rdxa_jb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="afdj8ubap"/><path class="i_eawsnbu"/><path class="rdxa_jb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scroll-duo" /></template>
