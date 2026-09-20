<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGx7x4qc8e"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="yvwj1hb-x"/></mask></defs><circle mask="url(#SVGx7x4qc8e)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:thumbs-up-circle-filled" /></template>
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

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.yvwj1hb-x {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M6.5 11a1 1 0 0 0-1 1v5.5a1 1 0 0 0 1 1H9a1 1 0 0 0 1-1V12a1 1 0 0 0-1-1zm1.25 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2m6.731-9.335a.167.167 0 0 0-.273.056l-.194 1.165A5.16 5.16 0 0 1 12.23 12v4.681l4.196.84q.042.008.082.02a1.43 1.43 0 0 0 1.603-.63l.217-.353l.507-1.338a3.9 3.9 0 0 0-.018-2.809l-.31-.621a1.43 1.43 0 0 0-1.272-.79H15.73q-.064 0-.125-.008a1 1 0 0 1-1.096-1.235l.15-.594a2 2 0 0 0 .057-.547l-.014-.41a.85.85 0 0 0-.202-.521zm-3.428 10.82l4.947.989a3.43 3.43 0 0 0 3.815-1.516l.257-.416a1 1 0 0 0 .1-.206l.534-1.409a5.9 5.9 0 0 0-.044-4.292a1 1 0 0 0-.037-.082l-.329-.659A3.43 3.43 0 0 0 17.231 9h-.525q.018-.225.01-.453l-.014-.41a2.85 2.85 0 0 0-.764-1.844l-.043-.042c-1.19-1.192-3.226-.628-3.634 1.006l-.017.079l-.203 1.221a3.16 3.16 0 0 1-1.354 2.104a1 1 0 0 0-.456.839v5.98a1 1 0 0 0 .822 1.004");
}

</style>
