<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGQJcUlc9g"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="dzwsyj5ji"/><path class="rsmtrct-q"/></g></mask></defs><circle mask="url(#SVGQJcUlc9g)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:paperclip-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.dzwsyj5ji {
  d: path("M12.109 5.493a4.5 4.5 0 1 1 6.513 6.211l-5.349 5.608a2.75 2.75 0 0 1-3.981-3.795l4.484-4.707a1 1 0 0 1 1.448 1.38l-4.484 4.706a.75.75 0 0 0 1.086 1.036l5.349-5.608a2.5 2.5 0 0 0-3.619-3.451l-4.83 5.066a1 1 0 0 1-1.448-1.38z");
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.rsmtrct-q {
  d: path("M7.824 18.68c-.372-.355-.726-.926-1.036-1.605c-.6-1.31-.168-2.929 1.004-4.159l4.384-4.596a1 1 0 1 0-1.447-1.38l-4.384 4.596c-1.549 1.624-2.417 4.095-1.376 6.37c.352.77.833 1.609 1.475 2.22c.632.604 1.476 1.04 2.25 1.354c2.345.95 4.797-.061 6.345-1.715l5.691-6.082a1 1 0 1 0-1.46-1.366l-5.692 6.08c-1.173 1.255-2.785 1.775-4.133 1.23c-.68-.277-1.255-.599-1.621-.948");
}

</style>
