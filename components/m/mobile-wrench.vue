<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8h3rj7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-wrench" /></template>
<style>
.qw8h3rj7b {
  fill: currentColor;
  d: path("M12.588 6.088q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v1.853q-.383-.121-.768-.197q-.384-.076-.809-.076q-2.121 0-3.618 1.497t-1.497 3.618q0 1.718 1.016 3.032T14.961 22zm12.259 0l-2.315-2.277q-.237.125-.508.172t-.552.047q-1.148 0-1.94-.791q-.79-.792-.79-1.934q0-.354.092-.692t.255-.637l1.51 1.51l1.034-1.06l-1.509-1.484q.298-.181.637-.265q.338-.083.711-.083q1.142 0 1.937.781t.794 1.93q0 .3-.06.571t-.184.527l2.302 2.277z");
}

</style>
