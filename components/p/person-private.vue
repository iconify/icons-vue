<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/frf5-licm.css';
import '../../css/h/h1tzoq9te.css';
import '../../css/y/yh0pkfbkw.css';
import '../../css/x/x2v4sktgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="frf5-licm"/><path class="h1tzoq9te"/><path clip-rule="evenodd" class="yh0pkfbkw"/><path clip-rule="evenodd" class="x2v4sktgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:person-private" /></template>
