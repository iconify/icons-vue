<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGBbHzFdQq"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="j8iw8bxhw"/><path class="qbhzle8yh"/><path class="eq2a2jegu"/></g></mask></defs><circle mask="url(#SVGBbHzFdQq)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:person-plus-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.eq2a2jegu {
  d: path("M4 17.833c0-3.295 2.79-5.766 6.013-5.766c3.232 0 5.987 2.478 5.987 5.766V20a1 1 0 1 1-2 0v-2.167c0-2.08-1.753-3.766-3.987-3.766c-2.24 0-4.013 1.692-4.013 3.766l.002 2.166a1 1 0 0 1-2 .002z");
}

.ft5dv1b6b {
  fill: none;
}

.j8iw8bxhw {
  d: path("M14.45 10.75a1 1 0 0 1 1-1h5.25a1 1 0 1 1 0 2h-5.25a1 1 0 0 1-1-1");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.qbhzle8yh {
  d: path("M18 14.5a1 1 0 0 1-1-1V8.25a1 1 0 1 1 2 0v5.25a1 1 0 0 1-1 1M10 8c-.792 0-1.5.679-1.5 1.6s.708 1.6 1.5 1.6s1.5-.679 1.5-1.6S10.792 8 10 8M6.5 9.6C6.5 7.65 8.03 6 10 6s3.5 1.65 3.5 3.6s-1.53 3.6-3.5 3.6s-3.5-1.65-3.5-3.6");
}

</style>
