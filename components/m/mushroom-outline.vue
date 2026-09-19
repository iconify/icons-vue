<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g-roh6blq.css';
import '../../css/p/plb01ybpw.css';
import '../../css/v/v74qb470j.css';
import '../../css/r/risyq2_-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g-roh6blq"/><path class="plb01ybpw"/><path class="v74qb470j"/><path class="risyq2_-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:mushroom-outline" /></template>
