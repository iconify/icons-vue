<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hjzzbm_-c.css';
import '../../css/w/w1o7y9xxt.css';
import '../../css/s/skf2rrc2o.css';
import '../../css/q/q79iqun2t.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="hjzzbm_-c"/><path clip-rule="evenodd" class="w1o7y9xxt"/><path class="skf2rrc2o"/><path clip-rule="evenodd" class="q79iqun2t"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:money-note-circle-filled" /></template>
