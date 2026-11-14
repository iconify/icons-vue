<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eryv9qdmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:story-draw" /></template>
<style>
.eryv9qdmq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m6.303-.613q-1.469.267-2.724 2.778q-.033.066-.052.137q-.02.071-.025.145t.004.147t.032.143q.024.07.06.134q.037.065.085.12q.049.056.107.101q.059.046.125.079t.137.052t.145.025t.147-.004t.143-.032q.07-.024.134-.06q.065-.037.12-.085q.056-.049.101-.107q.046-.059.079-.125q.92-1.839 1.651-1.972q.477-.087 1.007.972q.957 1.915 2.421 1.915t2.421-1.915q.033-.066.052-.137q.02-.071.025-.145t-.004-.147t-.032-.143t-.06-.134t-.085-.12t-.107-.101t-.125-.079t-.137-.052q-.071-.02-.145-.025t-.147.004t-.143.032t-.134.06t-.12.085t-.101.107t-.079.125q-.543 1.085-1.079 1.085t-1.079-1.085q-1.033-2.066-2.618-1.778");
}

</style>
