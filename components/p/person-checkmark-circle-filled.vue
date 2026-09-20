<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGDoKrYcaB"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="c00_yfb_e"/><path class="snwf-abkx"/><path class="tea6p9bmt"/></g></mask></defs><circle mask="url(#SVGDoKrYcaB)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:person-checkmark-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.c00_yfb_e {
  d: path("M10 8c-.792 0-1.5.679-1.5 1.6s.708 1.6 1.5 1.6s1.5-.679 1.5-1.6S10.792 8 10 8M6.5 9.6C6.5 7.65 8.03 6 10 6s3.5 1.65 3.5 3.6s-1.53 3.6-3.5 3.6s-3.5-1.65-3.5-3.6");
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

.snwf-abkx {
  d: path("M4 17.833c0-3.295 2.79-5.766 6.013-5.766c3.232 0 5.987 2.478 5.987 5.766V20a1 1 0 1 1-2 0v-2.167c0-2.08-1.753-3.766-3.987-3.766c-2.24 0-4.013 1.692-4.013 3.766l.002 2.166a1 1 0 0 1-2 .002zM21.597 7.126a1 1 0 0 1 .388 1.36l-2.777 5a1 1 0 1 1-1.749-.972l2.778-5a1 1 0 0 1 1.36-.388");
}

.tea6p9bmt {
  d: path("M14.775 10.153a1 1 0 0 1 1.405-.156l2.778 2.222a1 1 0 1 1-1.25 1.562l-2.777-2.222a1 1 0 0 1-.156-1.406");
}

</style>
