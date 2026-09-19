<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/g/gg4963rit.css';
import '../../css/y/y3tgw9b4u.css';
import '../../css/c/c8nsbsbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="gg4963rit"/><path class="y3tgw9b4u"/><path class="c8nsbsbjx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:toolbox" /></template>
