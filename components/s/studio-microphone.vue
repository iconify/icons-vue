<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cwoov0b5l.css';
import '../../css/a/au_fk_y7g.css';
import '../../css/t/towtafbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cwoov0b5l"/><path class="au_fk_y7g"/><path class="towtafbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:studio-microphone" /></template>
