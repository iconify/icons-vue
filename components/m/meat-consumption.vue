<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejxmaybul.css';
import '../../css/l/l15-dgb0q.css';
import '../../css/r/r0u4s_baz.css';
import '../../css/i/ih0llfv8g.css';
import '../../css/r/rpvb-o6bq.css';
import '../../css/l/l0bn-3b4l.css';
import '../../css/h/ha4zerbvv.css';
import '../../css/z/z_9tf2n6g.css';
import '../../css/m/mkavb3bpo.css';
import '../../css/l/l4jawln8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ejxmaybul"/><path class="l15-dgb0q"/><circle class="r0u4s_baz"/><path class="ih0llfv8g"/><g class="rpvb-o6bq"><g class="l0bn-3b4l"><path class="ha4zerbvv"/><path class="z_9tf2n6g"/><circle class="mkavb3bpo"/></g><path class="l4jawln8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:meat-consumption" /></template>
