<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sbozl5bay.css';
import '../../css/s/spjfx4bcg.css';
import '../../css/p/pja9v0dnj.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sbozl5bay"/><path clip-rule="evenodd" class="spjfx4bcg"/><path clip-rule="evenodd" class="pja9v0dnj"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:planet-off" /></template>
