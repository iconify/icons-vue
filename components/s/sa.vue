<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l7nq8oi5h.css';
import '../../css/e/e4o1ae02c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="l7nq8oi5h"/><path class="e4o1ae02c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:sa" /></template>
