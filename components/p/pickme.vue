<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="s7wy_--0l"/><circle class="c4i-1rp4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pickme" /></template>
<style>
.c4i-1rp4z {
  cx: 25.157px;
  cy: 15.135px;
  r: 3.854px;
}

.s7wy_--0l {
  d: path("M9.5 5.5h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4H27.502l-.034-12.719c0-1.541.407-1.906 1.543-1.541l5.395 5.395c2.082 1.992 2.943-.592 2.313-1.541q-2.85-4.065-7.708-8.479c-2.475-1.524-4.416-.349-7.164-1.768c-2.75-1.42-5.672-6.852-6.712-9.024s-3.623-2.172-2.762.412s2.443 8.695 5.845 11.92c.704 1.052.68 1.063.771 2.313V42.5H9.5c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
