<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v_7nsv_zm.css';
import '../../css/h/h8am0cw8x.css';
import '../../css/j/jn6ooqbss.css';
import '../../css/x/x0bohhy_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v_7nsv_zm"/><path class="h8am0cw8x"/><path class="jn6ooqbss"/><path class="x0bohhy_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunset-outline" /></template>
