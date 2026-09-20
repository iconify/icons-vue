<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGHzLgHdeH"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="qp36x27yi"/><path class="qm9t1dvlo"/><path class="d_shy8bkf"/></g></mask></defs><circle mask="url(#SVGHzLgHdeH)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:studio-light-side-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.d_shy8bkf {
  d: path("M13.793 8.959a1 1 0 0 1 0-1.415l3-3a1 1 0 1 1 1.414 1.415l-3 3a1 1 0 0 1-1.414 0m4.414 8a1 1 0 0 1-1.414 0l-3-3a1 1 0 0 1 1.414-1.415l3 3a1 1 0 0 1 0 1.415");
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

.qm9t1dvlo {
  d: path("M7.5 8.752a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2zm6 0h-4v4h4z");
}

.qp36x27yi {
  d: path("M16.89 7.456C18.22 6.57 20 7.523 20 9.12v3.263c0 1.597-1.78 2.55-3.11 1.664l-2.945-1.963l.888-1.332l-.888-1.333zm-1.337 3.296L18 12.383V9.12zm1.361 10.406a1 1 0 0 1-1.32.507L12.5 20.29v.962a1 1 0 1 1-2 0v-.962l-3.094 1.375a1 1 0 1 1-.812-1.827l3.906-1.736v-3.85a1 1 0 0 1 2 0v3.85l3.906 1.736a1 1 0 0 1 .508 1.32");
}

</style>
