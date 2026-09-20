<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ou9207p9w.css';
import '../../css/n/n7fs0pb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<g class="ft5dv1b6b"><circle class="ou9207p9w"/><path class="n7fs0pb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:polygon" /></template>
