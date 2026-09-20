<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGK8t9jJbm"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="cz9flacfa"/><path class="lg1zm-xzo"/><path class="dahd--brr"/></g></mask></defs><circle mask="url(#SVGK8t9jJbm)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:shield-checkered-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.cz9flacfa {
  fill-rule: evenodd;
  d: path("M14.572 6.07a3 3 0 0 0-2.73 0L8.42 7.82c-.936.478-1.513 1.375-1.505 2.338c.015 1.777.201 4.051.877 5.51c.73 1.574 2.504 3.205 4.011 4.37a2.274 2.274 0 0 0 2.808 0c1.507-1.165 3.28-2.796 4.011-4.37c.676-1.459.863-3.733.877-5.51c.008-.963-.569-1.86-1.504-2.338zm-3.64-1.78a5 5 0 0 1 4.55 0l3.423 1.749c1.53.782 2.609 2.33 2.594 4.135c-.014 1.785-.188 4.45-1.062 6.335c-.953 2.053-3.082 3.936-4.603 5.112a4.274 4.274 0 0 1-5.254 0c-1.52-1.176-3.65-3.06-4.602-5.112c-.875-1.886-1.048-4.55-1.063-6.335C4.901 8.37 5.98 6.821 7.51 6.04z");
}

.dahd--brr {
  d: path("M5.5 12.75h7.207a.5.5 0 0 1 .5.5v8.5l-4.533-1.983z");
}

.ft5dv1b6b {
  fill: none;
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.lg1zm-xzo {
  d: path("m12.725 4.75l7.226 3.368v5.132h-6.726a.5.5 0 0 1-.5-.5z");
}

</style>
