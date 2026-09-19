<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pac306byp.css';
import '../../css/n/nwrl2rjgh.css';
import '../../css/c/c80aj8b-s.css';
import '../../css/c/cwstqz83y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pac306byp"/><path clip-rule="evenodd" class="nwrl2rjgh"/><path class="c80aj8b-s"/><path clip-rule="evenodd" class="cwstqz83y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-outline" /></template>
