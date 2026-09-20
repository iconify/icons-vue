<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="zuqyrkbnd"/><g class="k2u_fybwn"><circle class="xii8hmbyr"/><circle class="r5fl0lb3y"/><circle class="bkx_pysua"/><circle class="l-elexbss"/><circle class="ho4lh1bfe"/><circle class="u48ttbm5f"/><circle class="g5q-qcc2j"/><circle class="aqfznfb6t"/></g><path class="tx8rp-s9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:new-moon-face" /></template>
<style>
.aqfznfb6t {
  cx: 6px;
  cy: 26px;
  r: 2px;
}

.bkx_pysua {
  cx: 22px;
  cy: 5px;
  r: 2px;
}

.g5q-qcc2j {
  cx: 32px;
  cy: 19px;
  r: 2px;
}

.ho4lh1bfe {
  cx: 30px;
  cy: 9px;
  r: 1px;
}

.k2u_fybwn {
  fill: var(--svg-color--5b6876, #5b6876);
}

.l-elexbss {
  cx: 3px;
  cy: 18px;
  r: 1px;
}

.r5fl0lb3y {
  cx: 24.5px;
  cy: 28.5px;
  r: 3.5px;
}

.tx8rp-s9g {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M18 24.904c-7 0-9-2.618-9-1.381C9 24.762 13 28 18 28s9-3.238 9-4.477c0-1.237-2 1.381-9 1.381M27 15a3 3 0 1 1-6 0a3 3 0 0 1 6 0m-12 0a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

.u48ttbm5f {
  cx: 16px;
  cy: 31px;
  r: 1px;
}

.xii8hmbyr {
  cx: 9.5px;
  cy: 7.5px;
  r: 3.5px;
}

.zuqyrkbnd {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M36 18c0 9.94-8.06 18-18 18c-9.941 0-18-8.06-18-18C0 8.059 8.059 0 18 0c9.94 0 18 8.059 18 18");
}

</style>
