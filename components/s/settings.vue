<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/d/dem5xxbcs.css';
import '../../css/o/o22ei45em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 3)" class="jtowsomii"><path class="dem5xxbcs"/><circle class="o22ei45em"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:settings" /></template>
