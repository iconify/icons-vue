<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mrknojtdi.css';
import '../../css/z/zunmuyb3r.css';
import '../../css/b/bwdud_gdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mrknojtdi"/><path class="zunmuyb3r"/><path clip-rule="evenodd" class="bwdud_gdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:toggle-right-duotone" /></template>
