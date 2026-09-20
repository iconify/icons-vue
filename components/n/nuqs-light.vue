<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uk0l00b2f.css';
import '../../css/d/dezuy7r0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path class="uk0l00b2f"/><path class="dezuy7r0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nuqs-light" /></template>
