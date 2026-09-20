<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5r1txb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:navigation-outline-rounded" /></template>
<style>
.q5r1txb-j {
  fill: currentColor;
  d: path("m12 18l-6.45 2.75q-.325.125-.612.063t-.488-.263t-.262-.5t.062-.625L11.075 4.05q.125-.3.388-.45T12 3.45t.537.15t.388.45l6.825 15.375q.125.325.062.625t-.262.5t-.488.263t-.612-.063zm-4.9-.1l4.9-2.1l4.9 2.1l-4.9-11zm4.9-2.1");
}

</style>
