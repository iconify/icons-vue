<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gte0u8hff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wrong-location-sharp" /></template>
<style>
.gte0u8hff {
  fill: currentColor;
  d: path("M13.143 11.259q.473-.472.473-1.143q0-.672-.473-1.144Q12.671 8.5 12 8.5t-1.143.472t-.472 1.144q0 .67.472 1.143q.472.472 1.143.472t1.143-.472M12 21.019q-3.525-3.117-5.31-5.814q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3q.252 0 .462.021t.48.033L14.9 5.012l-2.1 2.1l3.21 3.21l2.1-2.1l.929.934q.023.288.04.567t.017.573q0 2.212-1.785 4.909q-1.786 2.697-5.311 5.814m4.01-13.2l-.708-.708l2.1-2.1l-2.1-2.1l.708-.707l2.1 2.1l2.1-2.1l.707.707l-2.1 2.1l2.1 2.1l-.707.708l-2.1-2.1z");
}

</style>
