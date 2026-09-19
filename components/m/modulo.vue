<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/x/x4q8rjbot.css';
import '../../css/l/llc6ycc6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="x4q8rjbot"/><path class="llc6ycc6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:modulo" /></template>
