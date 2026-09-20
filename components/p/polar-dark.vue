<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kzuu6vb4l.css';
import '../../css/p/pin2338sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGDTtXObki)"><path clip-rule="evenodd" class="kzuu6vb4l"/></g><defs><clipPath id="SVGDTtXObki"><path class="pin2338sh"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:polar-dark" /></template>
