<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/u/ufx_3tb7d.css';
import '../../css/w/wtf0wdbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 7)" class="jtowsomii"><circle class="ufx_3tb7d"/><path class="wtf0wdbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:toggle" /></template>
