<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/alp7xrb4q.css';
import '../../css/g/g6lp7acdk.css';
import '../../css/b/b2bxplbwo.css';
import '../../css/x/xu-zhibit.css';
import '../../css/f/fh_crz1ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="alp7xrb4q"/><rect class="g6lp7acdk"/><path class="b2bxplbwo"/><rect class="xu-zhibit"/><path class="fh_crz1ad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:rv" /></template>
