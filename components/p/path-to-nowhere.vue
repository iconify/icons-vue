<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="aqw0tdnho"/><path class="edao_w29w"/><path class="k1suyaclq"/><path class="leb94hnbh"/><path class="rjx2dkj9s"/><path class="l3iw5ebls"/><path class="w0-4aebgp"/><path class="z0fe6zanz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:path-to-nowhere" /></template>
<style>
.aqw0tdnho {
  cx: 24.467px;
  cy: 24.664px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.edao_w29w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.729 19.617c.897 7.065 3.925 13.85 5.44 14.439s6.055 3.006 9.027 1.854s6.673-5.47 6.954-6.48c2.13.673 3.028-3.87 3.028-3.87");
}

.k1suyaclq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.215 17.738c1.935.59 2.467 4.963 2.467 4.963m.197 2.999c0-.476.07-.696.07-.696m1.724-.677c.364.196.897.336.897.336m-3.476 5.552c1.542-1.318 2.327-1.514 3.027-1.402c.673-.56 2.524-.533 3.365-.196m-9.656 5.718c2.198 3.899-.306 10.996-.306 10.996m14.99-14.827c.187 6.075 2.321 12.412 2.321 12.412M14.58 22.953c1.065-2.663 3.168-3.84 6-2.383c-2.664 2.804-6 2.383-6 2.383m11.299-3.869c1.513-1.178 3.027-1.71 5.158-.645c-.588 1.318-3.168 1.318-5.159.645m-7.429-1.346c-2.075-.028-4.402 2.2-4.402 2.2m.424 7.276c-1.77-1.373-2.527-1.092-2.527-1.092c-.701 3.56.407 6.584 4.956 6.572");
}

.l3iw5ebls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.785 41.178c-1.206-4.823 5.944-8.44 5.636-10.674c.476 3.3.392 6.384.392 6.384c1.85-3.673 1.319-9.622 1.319-9.622");
}

.leb94hnbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.372 44.587c1.4-4.721-.497-9.46-4.736-11.893c-1.683-.965-5.3-13.47-1.851-20.31s7.374-5.44 7.374-5.44c-.981-.981-1.07-2.086-1.07-2.086M21.28 7.7c4.627 3.646 7.262 7.066 6.477 15.59");
}

.rjx2dkj9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.221 15.401s5.61 12.179 16.265 12.038c-.841-11.747-9.71-22.16-9.71-22.16");
}

.w0-4aebgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.536 33.505c-.392 3.757.269 8.022.269 8.022m-3.739-5.847c-4.739-.145-9.46.129-14.334 2.947M17.383 26.43s-1.913-2.86-3.154-5.636s-.694-10.913 5.636-10.472c1.22-1.093 2.817-.717 2.817-.717");
}

.z0fe6zanz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.094 8.358c1.619 2.68 1.43 7.285 1.43 7.285m-6.365-8.699c1.002.834 2.706 3.378 2.706 3.378m-2.587 10.935l.627 1.151M12.03 32.932c-2.301.115-4.88 1.853-5.077 1.853s-1.523-.122-1.523-.122M3.262 21.1c1.645-.193 2.168-1.483 2.168-1.483s.822-4.575 3.135-3.143m15.902.241c1.215-1.346 2.658-1.616 2.658-1.616");
}

</style>
