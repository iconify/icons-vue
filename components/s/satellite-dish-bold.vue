<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b6j2gst7o.css';
import '../../css/j/j9o98-sii.css';
import '../../css/b/b0agiabox.css';
import '../../css/h/hef7o05pd.css';
import '../../css/o/ohm_3ubgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="b6j2gst7o"/><path class="j9o98-sii"/><circle class="b0agiabox"/><path class="hef7o05pd"/><path class="ohm_3ubgl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:satellite-dish-bold" /></template>
