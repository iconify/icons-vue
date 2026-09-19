<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x1b0lrbit"/><g class="v6fp4y12w"><path class="f-y0w3hnw"/><ellipse class="rk94co-9q"/></g><path class="o23i-o7yk"/><path class="ue53aibtk"/><path class="iy-7d8uys"/><path class="y2m1w_bfu"/><circle class="v_gj-52vp"/><path class="fyadelbiu"/><path class="uoihd63rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:teacup-without-handle" /></template>
<style>
.f-y0w3hnw {
  d: path("M57 31.7H7s.7 11.1 7.3 20.1c2.5 3.3 8.3 8.1 17.7 8.1c9.3 0 15.2-4.8 17.7-8.1c6.6-9 7.3-20.1 7.3-20.1");
}

.fyadelbiu {
  fill: var(--svg-color--b59267, #b59267);
  d: path("M19.9 38.2h1v10h-1z");
}

.iy-7d8uys {
  fill: var(--svg-color--4e6b20, #4e6b20);
  d: path("m25.5 52l-4.3-5.7l-6.1 3.5l-1.4 6.5l10.5 2.1z");
}

.o23i-o7yk {
  fill: var(--svg-color--d2d8d9, #d2d8d9);
  d: path("M32 27c10.6 0 19.5 2.7 21.5 6.4c.3-.5.5-1.1.5-1.6c0-4.4-9.8-8-22-8s-22 3.6-22 8c0 .6.2 1.1.5 1.6c2-3.7 10.9-6.4 21.5-6.4");
}

.rk94co-9q {
  cx: 32px;
  cy: 31.7px;
  rx: 25px;
  ry: 9.7px;
}

.ue53aibtk {
  fill: var(--svg-color--96b269, #96b269);
  d: path("M32 39.7c10.6 0 19.5-2.7 21.5-6.4c-2-3.6-10.9-6.3-21.5-6.3s-19.5 2.7-21.5 6.4c2 3.6 10.9 6.3 21.5 6.3");
}

.uoihd63rl {
  fill: var(--svg-color--a6aeb0, #a6aeb0);
  d: path("M33.3 11.4C29.6 7.6 32.1 2 32.1 2s-7.8 7.4-2.9 12.5c5.7 5.9 2.9 9.5 2.9 9.5s7-6.6 1.2-12.6m-11 3.4c-2.8-2.7-.9-6.8-.9-6.8s-5.8 5.4-2.1 9.1c4.2 4.3 2.1 6.9 2.1 6.9s5.2-4.8.9-9.2m22 0c-2.8-2.7-.9-6.8-.9-6.8s-5.8 5.4-2.1 9.1c4.2 4.3 2.1 6.9 2.1 6.9s5.2-4.8.9-9.2");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.v_gj-52vp {
  cx: 20.4px;
  cy: 48.7px;
  r: 1.2px;
  fill: var(--svg-color--4e6b20, #4e6b20);
}

.v6fp4y12w {
  fill: var(--svg-color--eff6f7, #eff6f7);
}

.x1b0lrbit {
  fill: var(--svg-color--d2d8d9, #d2d8d9);
  d: path("M45.6 55.3H18.4s.4 2.6 4 4.8c1.3.8 4.5 1.9 9.6 1.9s8.3-1.1 9.6-1.9c3.7-2.1 4-4.8 4-4.8");
}

.y2m1w_bfu {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("m24.7 52.5l-3.5-6.2l-6.6 2.6l-2.2 6.1l10 3.7z");
}

</style>
