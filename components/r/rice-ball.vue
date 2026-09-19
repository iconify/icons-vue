<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lfo9zmb1i.css';
import '../../css/w/w0icurbfp.css';
import '../../css/k/kv9lyjb2a.css';
import '../../css/e/e7eydrofg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lfo9zmb1i"/><path class="w0icurbfp"/><path class="kv9lyjb2a"/><path class="e7eydrofg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:rice-ball" /></template>
