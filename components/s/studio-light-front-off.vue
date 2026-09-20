<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ihnlsybak.css';
import '../../css/n/nncaqob0h.css';
import '../../css/s/sspjfbb1z.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ihnlsybak"/><path clip-rule="evenodd" class="nncaqob0h"/><path clip-rule="evenodd" class="sspjfbb1z"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:studio-light-front-off" /></template>
