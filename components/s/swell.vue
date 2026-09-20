<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGMrG11d4e)" class="u15uno9eb"/><path fill="url(#SVGsvjHzdXA)" clip-rule="evenodd" class="mhqnw9_pu"/><path class="b3xr52r4p"/><defs><linearGradient id="SVGMrG11d4e" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="iz18d3bnd"/><stop offset="1" class="a2zt197-f"/></linearGradient><linearGradient id="SVGsvjHzdXA" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="f22onaben"/><stop offset="1" class="xzb1dfbiv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:swell" /></template>
<style>
.a2zt197-f {
  stop-color: var(--svg-color--3066ed, #3066ed);
}

.b3xr52r4p {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.606 13.222l-.016.016l-.022.022l-4.239 4.19c-.738.73-1.936.73-2.674 0l-1.17-1.157a.208.208 0 0 1 .086-.349q1.882-.575 3.058-1.328q2.802-1.792 4.977-1.394m-.89-3.446c1.566.488 1.383 1.628 1.404 2.077q-2.571-1.335-6.186.978q-2.693 1.725-4.514 1.422c-1.213-.202-1.486-1.668-1.54-2.058q2 1 5.359-1.149q3.13-2.003 5.478-1.27M13.33 6.427l1.1 1.087a.208.208 0 0 1-.108.355q-2.388.476-3.82 1.392q-2.454 1.57-4.182 1.46l4.336-4.294a1.907 1.907 0 0 1 2.674 0");
}

.f22onaben {
  stop-color: var(--svg-color--7dacff, #7dacff);
}

.ft5dv1b6b {
  fill: none;
}

.iz18d3bnd {
  stop-color: var(--svg-color--2142cb, #2142cb);
}

.mhqnw9_pu {
  fill-rule: evenodd;
  d: path("M12 3.72a8.28 8.28 0 1 0 0 16.56a8.28 8.28 0 0 0 0-16.56M3 12a9 9 0 1 1 18 0a9 9 0 0 1-18 0");
}

.u15uno9eb {
  d: path("M12 20.64a8.64 8.64 0 1 0 0-17.28a8.64 8.64 0 0 0 0 17.28");
}

.xzb1dfbiv {
  stop-color: var(--svg-color--cedeff, #cedeff);
}

</style>
