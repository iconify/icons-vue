<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rlvea8b0i.css';
import '../../css/f/f59_fh1ap.css';
import '../../css/l/lewo1f2te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rlvea8b0i"/><path class="f59_fh1ap"/><path class="lewo1f2te"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-ban-duotone" /></template>
