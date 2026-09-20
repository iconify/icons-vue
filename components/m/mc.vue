<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGQLCokbqw)" clip-rule="evenodd" class="qr0zezhpm"/><path fill="url(#SVGNeg1yGCH)" class="zn93gsw1p"/><defs><linearGradient id="SVGQLCokbqw" x1="12" x2="12" y1="3" y2="17.906" gradientUnits="userSpaceOnUse"><stop class="bykak7b6q"/><stop offset=".89" class="f83mxmbxb"/></linearGradient><linearGradient id="SVGNeg1yGCH" x1="12.125" x2="12.125" y1="6.374" y2="20.976" gradientUnits="userSpaceOnUse"><stop offset=".15" class="jgtcky-7l"/><stop offset="1" class="t2bridb1q"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mc" /></template>
<style>
.bykak7b6q {
  stop-color: var(--svg-color--f4c251, #f4c251);
}

.f83mxmbxb {
  stop-color: var(--svg-color--e47236, #e47236);
}

.ft5dv1b6b {
  fill: none;
}

.jgtcky-7l {
  stop-color: var(--svg-color--e1602b, #e1602b);
}

.qr0zezhpm {
  fill-rule: evenodd;
  d: path("M12 3c4.961 0 9 4.039 9 9s-4.039 9-9 9s-9-4.039-9-9s4.039-9 9-9m0 12.937c-1.125-1-1.687-2.306-1.687-3.937S10.875 9.064 12 8.062c1.125 1.002 1.687 2.307 1.687 3.938s-.562 2.908-1.687 3.937");
}

.t2bridb1q {
  stop-color: var(--svg-color--edad3f, #edad3f);
}

.zn93gsw1p {
  d: path("M3.254 14.153c.034.056 2.008 3.527 5.231 3.47c1.052-.016 2.216-.702 3.516-1.687c1.125-1.001 1.687-2.306 1.687-3.937c0-1.632-.562-2.937-1.687-3.938c0 0 1.811-1.727 3.937-1.687c1.665.028 3.544 1.12 4.939 4.123a9.013 9.013 0 0 1-8.876 10.48a8.96 8.96 0 0 1-8.747-6.824");
}

</style>
