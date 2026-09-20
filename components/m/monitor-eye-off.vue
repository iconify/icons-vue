<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g6ybgx9-u.css';
import '../../css/t/tqi9df0br.css';
import '../../css/v/vve2dil0o.css';
import '../../css/g/gf77tvf2s.css';
import '../../css/a/a666lh9aj.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g6ybgx9-u"/><path clip-rule="evenodd" class="tqi9df0br"/><path clip-rule="evenodd" class="vve2dil0o"/><path class="gf77tvf2s"/><path clip-rule="evenodd" class="a666lh9aj"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:monitor-eye-off" /></template>
