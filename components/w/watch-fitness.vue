<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u8rdw4bir.css';
import '../../css/k/kzym1ogmg.css';
import '../../css/r/rn_p5ms7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="u8rdw4bir"/><rect class="kzym1ogmg"/><path clip-rule="evenodd" class="rn_p5ms7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:watch-fitness" /></template>
