<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sv_9e_bmt.css';
import '../../css/d/deafncc0t.css';
import '../../css/d/duhkb9blp.css';
import '../../css/n/nop9siewt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sv_9e_bmt"/><path class="deafncc0t"/><path class="duhkb9blp"/><path class="nop9siewt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tv-retro-outline" /></template>
