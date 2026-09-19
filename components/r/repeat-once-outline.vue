<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b8o27mgml.css';
import '../../css/o/of-k99bvu.css';
import '../../css/m/mzbt9lmsw.css';
import '../../css/n/nf6pszb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="b8o27mgml"/><path class="of-k99bvu"/><path clip-rule="evenodd" class="mzbt9lmsw"/><path class="nf6pszb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:repeat-once-outline" /></template>
