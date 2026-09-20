<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/njp_g6b2z.css';
import '../../css/h/hwz4pek1f.css';
import '../../css/o/ofdhnnb0y.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="njp_g6b2z"/><path clip-rule="evenodd" class="hwz4pek1f"/><path clip-rule="evenodd" class="ofdhnnb0y"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:megaphone-off" /></template>
