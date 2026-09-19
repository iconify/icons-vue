<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="hjkih7cbq"/><circle class="ilyg31otb"/><g class="n1mjunbsu"><path class="hvn1q0blo"/><path class="ps07q2b-n"/></g><path class="pquc_7bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:no-littering" /></template>
<style>
.hjkih7cbq {
  cx: 32px;
  cy: 32.1px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

.hvn1q0blo {
  d: path("M32.6 20.5h2.6c1 0 1.7-.6 1.7-1.4v-3.4c0-.8-.8-1.4-1.7-1.4h-2.6c-1 0-1.7.6-1.7 1.4v3.4c0 .7.8 1.4 1.7 1.4m6.9 1.5H28c-.8 0-1.5.5-1.5 1.2V29l-3.7 3v1.3l5.8-2.9l.7-6V50h3l1.5-11.6L35.3 50h3V24.3l1.3 11.6H41V23.2c0-.7-.7-1.2-1.5-1.2M20 34.3h2.8v3.8H20z");
}

.ilyg31otb {
  cx: 32px;
  cy: 32.1px;
  r: 24px;
  fill: var(--svg-color--333, #333);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.pquc_7bym {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("m9.263 13.592l4.243-4.243L54.8 50.644l-4.242 4.243z");
}

.ps07q2b-n {
  d: path("M23.8 38.9h2.8v3.8h-2.8zm-4.6 4.3H22V47h-2.8z");
}

</style>
