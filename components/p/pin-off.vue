<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/z/zb0z3vbgl.css';
import '../../css/p/pee5nxbvm.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="zb0z3vbgl"/><path class="pee5nxbvm"/></g><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:pin-off" /></template>
