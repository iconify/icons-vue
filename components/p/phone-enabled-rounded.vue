<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-qzwx4ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-enabled-rounded" /></template>
<style>
.p-qzwx4ih {
  fill: currentColor;
  d: path("M5.07 20q-.45 0-.76-.3T4 18.95v-2.434q0-.402.254-.713t.662-.41l2.103-.432q.37-.05.674.034t.55.347l2.138 2.177q1.2-.665 2.204-1.414q1.004-.75 1.875-1.62q.844-.858 1.589-1.817t1.36-2.076l-2.193-2.046q-.239-.2-.333-.513t-.025-.733l.496-2.385q.108-.402.412-.658q.303-.257.711-.257h2.473q.45 0 .75.31t.3.76q0 2.528-1.266 5.174t-3.536 4.935q-2.289 2.288-4.944 3.555Q7.598 20 5.069 20");
}

</style>
