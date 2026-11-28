<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kse2j4bnn"/><path clip-rule="evenodd" class="urwx4ybde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-sparkles-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kse2j4bnn {
  d: path("M4 11V22H22V4H11M16 4V22");
}

.urwx4ybde {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.549 1.374L6.42 3.58L8.626 4.451C8.852 4.54 9 4.758 9 5C9 5.242 8.852 5.46 8.626 5.549L6.42 6.42L5.549 8.626C5.46 8.852 5.242 9 5 9C4.758 9 4.54 8.852 4.451 8.626L3.58 6.42L1.374 5.549C1.148 5.46 1 5.242 1 5C1 4.758 1.148 4.54 1.374 4.451L3.58 3.58L4.451 1.374C4.54 1.148 4.758 1 5 1C5.242 1 5.46 1.148 5.549 1.374ZM10.843 7.234L11.387 8.613L12.766 9.157C12.907 9.212 13 9.349 13 9.5C13 9.651 12.907 9.788 12.766 9.843L11.387 10.387L10.843 11.766C10.788 11.907 10.651 12 10.5 12C10.349 12 10.212 11.907 10.157 11.766L9.613 10.387L8.234 9.843C8.093 9.788 8 9.651 8 9.5C8 9.349 8.093 9.212 8.234 9.157L9.613 8.613L10.157 7.234C10.212 7.093 10.349 7 10.5 7C10.651 7 10.788 7.093 10.843 7.234Z");
  stroke: none;
}

</style>
