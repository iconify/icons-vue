<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGJTvRsbGa)" class="arxpbdbrx"/><path class="q5kq8wb7j"/><path class="mmwz7bbjs"/><path class="ys_ew3lpy"/><path class="kso8y8bgx"/><path class="j8e8qcbok"/><path class="cuomn_bej"/><defs><linearGradient id="SVGJTvRsbGa" x1="8.719" x2="15.519" y1="4.5" y2="20.194" gradientUnits="userSpaceOnUse"><stop class="by59ceb5e"/><stop offset=".49" class="tg2wudbir"/><stop offset="1" class="prefjfggu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sph" /></template>
<style>
.arxpbdbrx {
  d: path("M12 13.125A5.063 5.063 0 1 0 12 3a5.063 5.063 0 0 0 0 10.125");
}

.by59ceb5e {
  stop-color: var(--svg-color--ccc, #ccc);
}

.cuomn_bej {
  fill: var(--svg-color--dfe02a, #dfe02a);
  d: path("M12.13 17.063c-.726.663-2.273 1.124-4.068 1.124h-.129c.726-.663 2.273-1.125 4.067-1.125z");
}

.ft5dv1b6b {
  fill: none;
}

.j8e8qcbok {
  fill: var(--svg-color--cf4e92, #cf4e92);
  d: path("M16.067 18.187h-.13c-1.794 0-3.34-.46-4.066-1.125H12c1.794 0 3.341.462 4.067 1.125");
}

.kso8y8bgx {
  fill: var(--svg-color--5dc9b5, #5dc9b5);
  d: path("M12 21c2.485 0 4.5-.881 4.5-1.969c0-1.087-2.015-1.968-4.5-1.968s-4.5.88-4.5 1.968S9.515 21 12 21");
}

.mmwz7bbjs {
  fill: var(--svg-color--bc266e, #bc266e);
  d: path("M15.938 18.188c2.485 0 4.5-.882 4.5-1.97c0-1.086-2.015-1.968-4.5-1.968c-2.486 0-4.5.882-4.5 1.969s2.014 1.968 4.5 1.968");
}

.prefjfggu {
  stop-color: var(--svg-color--c5c5c5, #c5c5c5);
}

.q5kq8wb7j {
  fill: var(--svg-color--ccb806, #ccb806);
  d: path("M8.062 18.188c2.486 0 4.5-.882 4.5-1.97c0-1.086-2.014-1.968-4.5-1.968c-2.485 0-4.5.882-4.5 1.969s2.015 1.968 4.5 1.968");
}

.tg2wudbir {
  stop-color: var(--svg-color--ededed, #ededed);
}

.ys_ew3lpy {
  fill: var(--svg-color--f2c01c, #f2c01c);
  d: path("M12 17.175c.36-.281.562-.607.562-.956s-.202-.675-.562-.956c-.36.28-.562.607-.562.956s.202.675.562.956");
}

</style>
