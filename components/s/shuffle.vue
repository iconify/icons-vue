<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/f/f9g5z2bmo.css';
import '../../css/k/kv6jg4bfo.css';
import '../../css/d/dxbxl11oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="f9g5z2bmo"/><path class="kv6jg4bfo"/><path class="dxbxl11oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:shuffle" /></template>
