<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/htd3bk08t.css';
import '../../css/t/t7ftagsyg.css';
import '../../css/n/nslp9ac8f.css';
import '../../css/d/dj40413uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="htd3bk08t"/><path clip-rule="evenodd" class="t7ftagsyg"/><path class="nslp9ac8f"/><path clip-rule="evenodd" class="dj40413uj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shopping-bags-outline" /></template>
