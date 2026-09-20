<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/m/mmre0ys1c.css';
import '../../css/e/e_45-ab-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="mmre0ys1c"/><path class="e_45-ab-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:mini-player" /></template>
