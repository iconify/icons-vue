<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ruo5rub3h.css';
import '../../css/g/gwszt1jdi.css';
import '../../css/j/jr913_bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ruo5rub3h"/><path class="gwszt1jdi"/><path class="jr913_bbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-superhero" /></template>
