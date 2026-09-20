<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf6ukb-7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-lock-sharp" /></template>
<style>
.hf6ukb-7i {
  fill: currentColor;
  d: path("M9 9h6V7q0-1.25-.875-2.125T12 4t-2.125.875T9 7zm9.52 12q-.84 0-1.42-.58T16.52 19q0-.385.136-.73t.379-.618L18.519 16l1.485 1.652q.242.273.379.618t.136.73q0 .839-.58 1.42t-1.42.58m-5.453-4.934q.434-.433.434-1.066t-.434-1.066T12 13.5t-1.066.434Q10.5 14.367 10.5 15t.434 1.066q.433.434 1.066.434t1.066-.434M5 21V9h3V7q0-1.671 1.165-2.835Q10.329 3 12 3t2.836 1.165T16 7v2h3v5.042q-.198-.011-.39-.027q-.193-.015-.39-.015q-1.762.096-2.981 1.383t-1.22 3.092q0 .69.192 1.321T14.795 21z");
}

</style>
