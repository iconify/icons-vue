<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hf21u3l1x.css';
import '../../css/w/wrc1g0bqn.css';
import '../../css/o/or6j5nbfo.css';
import '../../css/p/push3tb6c.css';
import '../../css/a/aqgsq_e6h.css';
import '../../css/u/ubud6bads.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hf21u3l1x"/><path class="wrc1g0bqn"/><path class="or6j5nbfo"/><path class="push3tb6c"/><path class="aqgsq_e6h"/><path class="ubud6bads"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-group-duotone" /></template>
