<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGaxaHue8k"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="i3ljovbal"/><path class="om_w2ebfc"/><path class="hqmxb4jea"/></g></mask></defs><circle mask="url(#SVGaxaHue8k)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:soft-drink-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.hqmxb4jea {
  d: path("M8.5 13.25a.75.75 0 0 1 0-1.5h9a.75.75 0 0 1 0 1.5zm6.818-8.022a.75.75 0 0 1 .364-1.456l4 1a.75.75 0 1 1-.364 1.456z");
}

.i3ljovbal {
  fill-rule: evenodd;
  d: path("M16.411 7H9.589a2.502 2.502 0 0 0-2.481 2.803l1.22 10A2.5 2.5 0 0 0 10.809 22h4.385a2.5 2.5 0 0 0 2.481-2.198l1.218-10A2.5 2.5 0 0 0 16.41 7M9.529 9.004L9.589 9h6.822a.5.5 0 0 1 .496.56l-1.217 10a.5.5 0 0 1-.496.44h-4.385a.5.5 0 0 1-.496-.44l-1.22-10a.5.5 0 0 1 .436-.556");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.om_w2ebfc {
  d: path("M12.217 17.72a.75.75 0 0 1-1.434-.44l4-13a.75.75 0 1 1 1.434.44z");
}

</style>
