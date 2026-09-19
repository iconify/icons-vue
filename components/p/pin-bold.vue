<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dm6lxrfug.css';
import '../../css/n/n94865b_n.css';
import '../../css/f/fbiosebgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dm6lxrfug"/><path clip-rule="evenodd" class="n94865b_n"/><path class="fbiosebgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pin-bold" /></template>
