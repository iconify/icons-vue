<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x3232dbkq.css';
import '../../css/d/dqs93qb0x.css';
import '../../css/e/erfydac2v.css';
import '../../css/l/lgov11kvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x3232dbkq"/><path class="dqs93qb0x"/><path class="erfydac2v"/><path class="lgov11kvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:save-1-outline" /></template>
