<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn55ge7zx.css';
import '../../css/p/pyk3u23xc.css';
import '../../css/m/mrpnast4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="tn55ge7zx"><path class="pyk3u23xc"/><path class="mrpnast4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:user-bold" /></template>
