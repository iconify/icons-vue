<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGLlg2eePH"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="pq8jcveoh"/><path class="sto89j2pk"/><path class="abueix02a"/><path class="ua4vtbc3u"/><path class="p9p2kdbbk"/></g></mask></defs><circle mask="url(#SVGLlg2eePH)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:persons-circle-filled" /></template>
<style>
.abueix02a {
  d: path("M9.25 9.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m0 2a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5m5.236 5.055a4.95 4.95 0 0 0-.832 2.748v.697a1 1 0 0 1-2 0v-.697c0-1.373.406-2.715 1.168-3.858zm1.971-1.055c-.792 0-1.532.396-1.971 1.055l-1.664-1.11a4.37 4.37 0 0 1 3.635-1.945h.197a1 1 0 0 1 0 2zm2.211 1.055c.543.813.832 1.77.832 2.748v.697a1 1 0 0 0 2 0v-.697a6.96 6.96 0 0 0-1.168-3.858z");
}

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

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.p9p2kdbbk {
  d: path("M16.5 12.5a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m0 2a3.25 3.25 0 1 0 0-6.5a3.25 3.25 0 0 0 0 6.5");
}

.pq8jcveoh {
  d: path("M7.236 13.055a4.95 4.95 0 0 0-.832 2.748v.697a1 1 0 0 1-2 0v-.697c0-1.373.406-2.715 1.168-3.858zM9.207 12c-.792 0-1.532.396-1.971 1.055l-1.664-1.11A4.37 4.37 0 0 1 9.207 10h.197a1 1 0 0 1 0 2zm2.211 1.055c.543.813.832 1.77.832 2.748v.697a1 1 0 0 0 2 0v-.697a6.96 6.96 0 0 0-1.168-3.858z");
}

.sto89j2pk {
  d: path("M9.447 12c.792 0 1.532.396 1.971 1.055l1.664-1.11A4.37 4.37 0 0 0 9.447 10H9.25a1 1 0 0 0 0 2z");
}

.ua4vtbc3u {
  d: path("M16.697 15.25c.792 0 1.532.396 1.971 1.055l1.664-1.11a4.37 4.37 0 0 0-3.635-1.945H16.5a1 1 0 1 0 0 2z");
}

</style>
