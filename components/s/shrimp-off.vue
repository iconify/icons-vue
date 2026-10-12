<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ji5xn82qf"/><path class="of9lbccwj"/><path class="dyj5n1gta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shrimp-off" /></template>
<style>
.dyj5n1gta {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 6.25h.01");
}

.ji5xn82qf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.56 4.48l-2.62-1.15q-.55-.24-1.15-.22l-2.74.06q-.6.02-1.14.29L6.56 4.62q-.54.27-.91.74L4.1 7.33q-.37.47-.51 1.05l-.54 2.33q-.14.58-.02 1.17l.47 2.21q.12.59.48 1.07l1.3 1.72q.36.48.89.76l1.8.94q.53.28 1.13.31l1.91.08q.6.03 1.15-.2l1.67-.69q.55-.23.25-.75l-.65-1.13q-.3-.52-.87-.33l-.62.2q-.57.19-1.17.12l-.64-.08q-.6-.07-1.11-.38l-.57-.36q-.51-.31-.84-.81l-.37-.57q-.33-.5-.42-1.09l-.09-.69q-.09-.59.08-1.16l.21-.68q.17-.57.57-1.02l.47-.52q.4-.45.95-.69l.67-.28q.55-.24 1.15-.22l.73.02q.6.02 1.14.29l.65.33q.54.27.93-.19l2.44-2.91q.39-.46-.16-.7m-8.44 3.4L6.37 5.39m-.33 6.18l-2.54-.23m4.02 4.14l-1.45 1.45");
}

.of9lbccwj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.68 17.75l3.39 2q.43.25-.05.38l-3.54.99q-.48.13-.45-.37l.19-2.75q.03-.5.46-.25m1.57-12c1.75-.5 3.5-1.5 4.5-3m-5.35 4c2 0 4.25.75 5.75 2.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
