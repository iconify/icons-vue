<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x1-7980yu.css';
import '../../css/j/j0b34b2wg.css';
import '../../css/l/lemrizwtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x1-7980yu"/><path class="j0b34b2wg"/><path class="lemrizwtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:web-window-xmark" /></template>
