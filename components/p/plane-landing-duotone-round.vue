<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r1qb5kekq"/><path class="zw3b81pam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-landing-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r1qb5kekq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m13.293 15.707l-1.636-1.636l-4.795.799a2.3 2.3 0 0 1-1.115-.081c-.816-.262-1.486-.937-1.423-1.837c.033-.467.267-.896.642-1.176l2.766-2.075L7.382 9h-.675c-1.119 0-2.414-.768-2.414-2c0-.453.18-.887.5-1.207l3-3c.32-.32.754-.5 1.207-.5c1.232 0 2 1.295 2 2.414v.675l.701.35l2.075-2.766c.28-.375.709-.609 1.176-.642c.9-.063 1.575.607 1.837 1.423c.117.36.145.742.081 1.115l-.799 4.795l1.636 1.636c1.536 1.536 2.951 3.462 1 5.414c-.692.692-1.538 1.096-2.528.899c-1.102-.221-2.116-1.128-2.886-1.899");
}

.zw3b81pam {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 12l-2-2l.884-5.303A1.37 1.37 0 0 0 15.5 3.5a.613.613 0 0 0-.924.066L12 7l-2-1V4.707c0-.453-.18-.887-.5-1.207a.707.707 0 0 0-1 0l-3 3a.707.707 0 0 0 0 1c.32.32.754.5 1.207.5H8l1 2l-3.434 2.576a.613.613 0 0 0-.066.924c.314.314.76.457 1.197.384L12 13l2 2c2 2 3 2 4 1s1-2-1-4M3 21h18");
}

</style>
