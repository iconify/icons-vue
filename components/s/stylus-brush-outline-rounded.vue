<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbwh_qb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-brush-outline-rounded" /></template>
<style>
.qbwh_qb7a {
  fill: currentColor;
  d: path("M12 15.135q-2.154 0-3.673-1.517t-1.52-3.687q0-2.046 1.4-3.85q1.4-1.802 3.08-3.248q.147-.137.311-.186t.337-.049q.265 0 .494.136q.229.135.354.382q.378.705.868 1.256t1.145 1.103q1.302 1.092 1.85 2.147q.546 1.055.546 2.29q0 2.19-1.519 3.706T12 15.135m2.97-2.22q1.222-1.22 1.222-3.003q0-.99-.492-1.894t-1.698-1.903q-.66-.536-1.166-1.122t-.932-1.385Q9.64 5.483 8.724 6.973t-.916 2.958q0 1.763 1.223 2.984q1.223 1.22 2.969 1.22t2.97-1.22M6.143 20q-.423 0-.658-.335q-.236-.336-.1-.74l.087-.242q.162-.452.533-.721t.848-.27h10.292q.477 0 .848.27t.533.72l.087.243q.136.404-.1.74q-.235.335-.658.335z");
}

</style>
