<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kgdi7ny9s.css';
import '../../css/p/p5k92nmzp.css';
import '../../css/w/w-3mh5pls.css';
import '../../css/i/ixisdkb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kgdi7ny9s"/><path clip-rule="evenodd" class="p5k92nmzp"/><path class="w-3mh5pls"/><path clip-rule="evenodd" class="ixisdkb9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:shield-exclamation-outline" /></template>
