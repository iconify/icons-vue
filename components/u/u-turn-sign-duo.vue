<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pz4ijodgd.css';
import '../../css/l/liksgb7co.css';
import '../../css/p/p5f4hpmqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pz4ijodgd"/><path class="liksgb7co"/><path class="p5f4hpmqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:u-turn-sign-duo" /></template>
