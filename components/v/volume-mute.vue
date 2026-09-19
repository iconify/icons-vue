<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkicofg7i.css';
import '../../css/c/casyzt9mq.css';
import '../../css/a/atjk8mbde.css';
import '../../css/a/az2by_uqa.css';
import '../../css/x/xxym7hbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="SVGxykMPeyg" width="13" height="13" x="30" y="18" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="dkicofg7i"/></mask><g class="casyzt9mq"><g mask="url(#SVGxykMPeyg)" class="atjk8mbde"><path class="az2by_uqa"/></g><path class="xxym7hbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:volume-mute" /></template>
