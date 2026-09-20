<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbzho5bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-cart-off-outline-rounded" /></template>
<style>
.zbzho5bqz {
  fill: currentColor;
  d: path("m15.825 13l-2-2h1.725l2.75-5H8.825l-2-2H19.95q.575 0 .888.488t.012 1.062l-3.55 6.4q-.275.5-.712.775t-.763.275M7 22q-.825 0-1.412-.587T5 20t.588-1.412T7 18t1.413.588T9 20t-.587 1.413T7 22m12.8.6L14.15 17H7.6q-1.1 0-1.675-.937T5.85 14.1l1.05-2.15L5.1 7.9L1.4 4.2q-.275-.275-.275-.7t.275-.7t.7-.275t.7.275l18.4 18.4q.275.275.288.688t-.288.712q-.275.275-.7.275t-.7-.275M12.15 15l-2-2H8.6l-1 2zm3.4-4h-1.725zm.038 10.413Q15 20.825 15 20t.588-1.412T17 18t1.413.588T19 20t-.587 1.413T17 22t-1.412-.587");
}

</style>
