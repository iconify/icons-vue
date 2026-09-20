<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ak0v_fljm.css';
import '../../css/q/q-0tevbrd.css';
import '../../css/s/st8r_y1jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><circle class="ak0v_fljm"/><path class="q-0tevbrd"/><path class="st8r_y1jl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:person-off" /></template>
