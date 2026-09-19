<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/cj97-rb3b.css';
import '../../css/g/g4ms8_b2o.css';
import '../../css/k/k4op9itrz.css';
import '../../css/d/de2eu9b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="cj97-rb3b"/><path class="g4ms8_b2o"/><path class="k4op9itrz"/><path class="de2eu9b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:replay-outline" /></template>
