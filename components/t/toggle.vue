<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctmlb8_7m.css';
import '../../css/b/b1zejdv0v.css';
import '../../css/s/s4_dt9c8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ctmlb8_7m"><path class="b1zejdv0v"/><path class="s4_dt9c8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:toggle" /></template>
