<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rxzk324rt"/><path class="ax5-6d64w"/><path class="f9j5aijuz"/><path class="doo6hubwt"/><path class="x0bmk5z4i"/><path class="sc-oracny"/><path class="zvqc9nbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:open-mailbox-with-raised-flag" /></template>
<style>
.ax5-6d64w {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M10 3a8 8 0 0 0-8 8v12h16V11a8 8 0 0 0-8-8");
}

.doo6hubwt {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M20 8.239C20 7.003 18.935 6 17.707 6H2.293C1.064 6 0 7.003 0 8.239v1.419l4.879 4.904l-4.78 4.806c.112.376.316.716.596.983l4.972-4.998l2.407 2.419a2.693 2.693 0 0 0 3.821 0l2.426-2.432l4.984 5.011c.28-.268.483-.608.596-.983l-4.792-4.818L20 9.646z");
}

.f9j5aijuz {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M20 18.761C20 19.997 18.935 21 17.707 21H2.293C1.064 21 0 19.997 0 18.761V8.239C0 7.003 1.064 6 2.293 6h15.414C18.935 6 20 7.003 20 8.239z");
}

.rxzk324rt {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M22 33c0 2.209-8 2.209-8 0V23a4 4 0 0 1 8 0z");
}

.sc-oracny {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M26 3H10a8 8 0 0 1 8 8v12h16V11a8 8 0 0 0-8-8");
}

.x0bmk5z4i {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M17.707 6H2.293C1.127 6 .121 6.906.02 8.055l8.408 8.397c.869.874 2.277.84 3.145-.035l8.41-8.346C19.889 6.914 18.877 6 17.707 6");
}

.zvqc9nbed {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M26 1h-4a2 2 0 0 0-2 2v12a2 2 0 0 0 4 0V7h2a2 2 0 0 0 2-2V3a2 2 0 0 0-2-2");
}

</style>
