<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b3oskyb6b.css';
import '../../css/i/i8f9unb0o.css';
import '../../css/t/t9muv9fus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="b3oskyb6b"/><path class="i8f9unb0o"/><path class="t9muv9fus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-mage" /></template>
