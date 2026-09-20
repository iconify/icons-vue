<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pqkimdt0f"><path class="smr-n7b5n"/><path class="t_owwrbyv"/><path class="mr-l2fluc"/><path class="wl4u8g3hp"/><path class="gwu80zbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:map" /></template>
<style>
.gwu80zbam {
  d: path("M13.028 10.579a.6.6 0 0 1 .943.431l.53 5.568a.597.597 0 0 1-.844.602l-5.084-2.32a.6.6 0 0 1-.1-1.032z");
}

.mr-l2fluc {
  d: path("M11.88 7.996a1.497 1.497 0 0 1 2.55.472l2.944 8.329a1.496 1.496 0 0 1-1.684 1.97l-8.677-1.608a1.497 1.497 0 0 1-.867-2.442z");
}

.pqkimdt0f {
  fill: none;
  stroke: var(--svg-color--e1ca7d, #e1ca7d);
}

.smr-n7b5n {
  d: path("M10.185 4.969c.806-1.399 2.823-1.399 3.63 0l6.902 11.969c.805 1.396-.203 3.142-1.816 3.142H5.1c-1.613 0-2.621-1.746-1.816-3.142z");
}

.t_owwrbyv {
  d: path("M10.911 6.915c.929-1.32 2.939-1.138 3.616.327l4.289 9.276c.677 1.463-.484 3.11-2.09 2.965l-10.168-.916c-1.606-.145-2.453-1.973-1.526-3.293z");
}

.wl4u8g3hp {
  d: path("M12.671 9.089a.898.898 0 0 1 1.496.43l1.85 7.461a.9.9 0 0 1-1.12 1.08l-7.38-2.123a.9.9 0 0 1-.376-1.509z");
}

</style>
