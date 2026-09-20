<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2q2ixbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-phone-rounded" /></template>
<style>
.p2q2ixbic {
  fill: currentColor;
  d: path("M12 7q-.885 0-1.68.302q-.797.302-1.46.842q-.177.154-.39.158t-.38-.161t-.146-.367t.197-.355q.828-.694 1.807-1.057Q10.927 6 12 6t2.052.363t1.808 1.056q.177.154.196.355t-.147.367t-.378.161t-.39-.158q-.664-.54-1.457-.842T12 7M8.845 3.567q-1.534.567-2.791 1.652q-.177.16-.385.176q-.207.017-.373-.149q-.165-.165-.13-.385q.034-.22.205-.38q1.385-1.2 3.092-1.84T12 2t3.537.64t3.092 1.84q.171.16.205.38q.035.22-.13.386q-.166.165-.373.15q-.208-.017-.385-.177q-1.258-1.085-2.791-1.652Q13.62 3 12 3t-3.155.567m1.54 17.664q-.69 0-1.153-.463t-.463-1.152v-7.231q0-.69.463-1.153t1.153-.463h3.23q.69 0 1.153.463t.463 1.153v7.23q0 .69-.463 1.153t-1.153.463z");
}

</style>
