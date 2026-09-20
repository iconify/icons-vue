<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/i/igb9ee7qs.css';
import '../../css/t/tlino87gl.css';
import '../../css/r/r-ctfne6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="igb9ee7qs"/><path class="tlino87gl"/><path class="r-ctfne6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:reuse" /></template>
