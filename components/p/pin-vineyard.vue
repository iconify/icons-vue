<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ro_w1ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-vineyard" /></template>
<style>
.u_ro_w1ou {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.803 6.307q1.092.166 1.697.821q.811-.878 2.5-.878q3.25 0 3.25 3.25q0 2.906-2.599 3.214q.099.468.099 1.036q0 2.906-2.599 3.214q.099.468.099 1.036q0 3.25-3.25 3.25T8.75 18q0-.568.099-1.036q-2.599-.308-2.599-3.214q0-.581.104-1.058q-.938-.178-1.652-.893q-.952-.953-.952-2.299t.952-2.299Q5.653 6.249 7 6.249t2.298.952l.075.077q.633-.814 1.912-.984q.321-3.126 3.622-3.538q.073-.009.147-.004t.145.025t.137.053t.124.078t.107.101t.085.12t.06.135t.032.143t.004.147t-.025.145t-.053.137t-.078.124q-.045.059-.101.107t-.12.085q-.064.036-.135.06q-.07.023-.143.032q-1.99.249-2.29 2.063");
}

</style>
