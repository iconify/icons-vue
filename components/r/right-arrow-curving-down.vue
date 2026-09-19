<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rehjs_-se"/><path class="e_7rmz46o"/><g class="n1mjunbsu"><path class="k8jt7lfjl"/><path class="ep86viwuq"/><circle class="nqqmrd0kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:right-arrow-curving-down" /></template>
<style>
.e_7rmz46o {
  fill: var(--svg-color--0867a3, #0867a3);
  d: path("M.207 48.574v8.339a6.88 6.88 0 0 0 6.874 6.882h50.04c3.8 0 6.876-3.08 6.876-6.882V6.883C53.103 46.45 13.947 48.963.205 48.578");
}

.ep86viwuq {
  d: path("M26.301 40.4c-.897.598-1.542 1.719-1.648 3.045l12.303 14.15l12.219-14.14c-.105-1.334-.748-2.457-1.649-3.055h-21.23");
}

.k8jt7lfjl {
  d: path("M18.939 7.597c.655 2.83.899 5.724.966 8.731c5.412.204 9.293 1.84 11.596 4.95c.566.739 1.01 1.611 1.321 2.618c.311 1 .509 1.975.587 2.914c.079.939.12 2.232.12 3.89v7.54h-.035v9.952h.824q2.09-.001 3.394-.422q1.307-.415 2.028-1.791c.479-.913.719-2.28.719-4.085V28.917c0-2.251-.129-4.283-.382-6.076a22 22 0 0 0-1.322-5.05c-.625-1.565-1.458-3-2.498-4.322c-1.349-1.677-2.883-3.045-4.597-4.121q-2.563-1.61-5.771-2.381c-1.891-.455-3.991-.676-6.239-.729c-.17.488-.411.94-.711 1.356");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nqqmrd0kc {
  cx: 20.14px;
  cy: 11.313px;
  r: 5.115px;
}

.rehjs_-se {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M63.998 56.913a6.877 6.877 0 0 1-6.876 6.882H7.081a6.88 6.88 0 0 1-6.874-6.882V6.879A6.877 6.877 0 0 1 7.081 0h50.042c3.8 0 6.876 3.08 6.876 6.879v50.034z");
}

</style>
