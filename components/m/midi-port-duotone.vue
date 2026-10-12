<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x65v47wkw.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/l/lr6ccgrbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x65v47wkw"/><path class="g4vvtk_cw"/><path class="lr6ccgrbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:midi-port-duotone" /></template>
