<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9eybmg"/><path class="tgxkbbc5w"/><path clip-rule="evenodd" class="p6a18oboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-bold-duotone" /></template>
<style>
.p6a18oboc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.58405 6.37604C1.9287 6.14628 2.39435 6.23941 2.62412 6.58405L3.43665 7.80286C4.03942 8.707 5.05417 9.25008 6.14081 9.25008H17.8593C18.946 9.25008 19.9607 8.707 20.5635 7.80285L21.376 6.58405C21.6058 6.23941 22.0715 6.14628 22.4161 6.37604C22.7608 6.60581 22.8539 7.07146 22.6241 7.4161L21.8116 8.6349C20.9306 9.95635 19.4475 10.7501 17.8593 10.7501H6.14081C4.55264 10.7501 3.06954 9.95635 2.18858 8.63491L1.37604 7.4161C1.14628 7.07146 1.23941 6.60581 1.58405 6.37604Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tgxkbbc5w {
  fill: currentColor;
  d: path("M19 15C19 16.1046 18.1046 17 17 17C15.8954 17 15 16.1046 15 15C15 13.8954 15.8954 13 17 13C18.1046 13 19 13.8954 19 15Z");
}

.xdj9eybmg {
  fill: currentColor;
  d: path("M9 15C9 16.1046 8.10457 17 7 17C5.89543 17 5 16.1046 5 15C5 13.8954 5.89543 13 7 13C8.10457 13 9 13.8954 9 15Z");
}

</style>
