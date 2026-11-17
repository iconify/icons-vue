<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glys747-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-map-pin-corner-fill" /></template>
<style>
.glys747-m {
  fill: currentColor;
  d: path("M13.95 10.831a6 6 0 0 0-2.886 4.286c-.04.192-.134.367-.272.506L5.414 21a1.292 1.292 0 0 1-2.173-1.193L4.753 13H4a1.65 1.65 0 0 1-1.508-2.32l3.33-7.492A2 2 0 0 1 7.65 2H13a1.582 1.582 0 0 1 1.372 2.364L11.723 9h1.671a.998.998 0 0 1 .556 1.831m1.234 9.946C13.952 19.518 13 17.798 13 16a4 4 0 0 1 .315-1.557c.2-.476.491-.907.857-1.271A3.98 3.98 0 0 1 17 12c1.064 0 2.078.418 2.828 1.172c.366.364.657.795.857 1.271c.209.492.316 1.022.315 1.557c0 2.286-1.588 4.594-3.445 5.832a1 1 0 0 1-1.11 0a8 8 0 0 1-1.261-1.055m1.11-4.069A1 1 0 0 0 17 17h.01a1 1 0 0 0 0-2H17a1 1 0 0 0-.925.621a.99.99 0 0 0 .216 1.085l.002.001Z");
}

</style>
