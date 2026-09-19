<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w0mumgb8o.css';
import '../../css/a/axd8_h6yq.css';
import '../../css/o/o44__fb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="w0mumgb8o"/><path class="axd8_h6yq"/><path class="o44__fb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:teapot" /></template>
