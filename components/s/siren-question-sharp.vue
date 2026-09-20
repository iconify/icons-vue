<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpta3lbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:siren-question-sharp" /></template>
<style>
.wpta3lbsh {
  fill: currentColor;
  d: path("M14.347 20.71q-1.25-1.25-1.25-3.056t1.25-3.057t3.057-1.25t3.057 1.25q1.25 1.251 1.25 3.057t-1.25 3.056t-3.057 1.251t-3.057-1.25m3.45-.328q.155-.156.155-.373q0-.218-.156-.373t-.373-.156t-.373.155t-.156.374t.156.373t.373.156t.373-.156m-.746-1.63h.752v-.172q0-.294.147-.478t.347-.384q.35-.3.55-.613t.2-.775q0-.687-.446-1.124t-1.177-.438q-.537 0-.999.338t-.663.874l.685.273q.113-.3.37-.525t.607-.225q.414 0 .645.207t.232.62q0 .294-.17.491q-.168.197-.368.397q-.15.15-.294.32t-.268.33q-.075.131-.112.29q-.038.16-.038.322zM3 20v-4.75h2.827v-5.115q0-2.56 1.797-4.347T12 4t4.376 1.788q1.797 1.787 1.797 4.347v.863l-.382-.024q-.189-.012-.387-.012q-2.804 0-4.758 1.96t-1.954 4.732q0 .602.105 1.191t.32 1.155zm5.673-7.058h1v-2.807q0-.96.684-1.634T12 7.827v-1q-1.38 0-2.354.964q-.973.963-.973 2.343z");
}

</style>
