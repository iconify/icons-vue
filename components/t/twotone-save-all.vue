<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzyaeegyg"/><path class="jbx312dhc"/><circle class="awuipgffp"/><path clip-rule="evenodd" class="s_bzsxc3r"/><path class="fntodxa3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-save-all" /></template>
<style>
.awuipgffp {
  cx: 13.5px;
  cy: 15.5px;
  r: 2.5px;
  fill: currentColor;
}

.fntodxa3b {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h10v2H4v10H2z");
}

.jbx312dhc {
  fill: currentColor;
  d: path("M9 9h6v2H9z");
}

.pzyaeegyg {
  fill: currentColor;
  d: path("M17 6H8a2 2 0 0 0-2 2v11a2 2 0 0 0 2 2h11c1.1 0 2-.9 2-2v-9zm2 13H8V8h8.17L19 10.83z");
}

.s_bzsxc3r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 10.83V19H8V8h8.17zM9 9h6v2H9zm4.5 9a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
