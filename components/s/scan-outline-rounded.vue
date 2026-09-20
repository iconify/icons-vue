<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi1c78nge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scan-outline-rounded" /></template>
<style>
.mi1c78nge {
  fill: currentColor;
  d: path("M6.616 21q-.667 0-1.141-.475T5 19.386V17q0-.213.144-.356t.357-.144t.356.144T6 17v2.385q0 .269.173.442t.443.173h10.769q.269 0 .442-.173t.173-.443V17q0-.213.144-.356t.357-.144t.356.144T19 17v2.385q0 .666-.475 1.14t-1.14.475zM5 4.616q0-.667.475-1.141T6.615 3h7.214q.331 0 .632.13t.518.349L18.52 7.02q.217.218.348.518t.131.632V11q0 .213-.144.356t-.357.144t-.356-.144T18 11V8h-3.2q-.34 0-.57-.23T14 7.2V4H6.616q-.27 0-.443.173T6 4.616V11q0 .213-.144.356t-.357.144t-.356-.144T5 11zM21.923 14.5H2.077q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h19.846q.213 0 .356.144t.144.357t-.144.356t-.356.143M12 16.5");
}

</style>
