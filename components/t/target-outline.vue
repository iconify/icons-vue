<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/q/q4z7accis.css';
import '../../css/r/rqbsb5yod.css';
import '../../css/b/b7h7ulb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="q4z7accis"/><path class="rqbsb5yod"/><path class="b7h7ulb6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:target-outline" /></template>
