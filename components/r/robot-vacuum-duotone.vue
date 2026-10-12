<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xzj1m4bfg.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/g/gx35_lbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xzj1m4bfg"/><path class="g4vvtk_cw"/><path class="gx35_lbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:robot-vacuum-duotone" /></template>
