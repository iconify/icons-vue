<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGFdxNteVk)" class="y962qp91i"/><path fill="url(#SVG5RDvhbGU)" class="pgrs20b-l"/><path class="lx_ophbum"/><defs><radialGradient id="SVGFdxNteVk" cx="0" cy="0" r="1" gradientTransform="matrix(19.1627 0 0 19.1429 18.884 2.994)" gradientUnits="userSpaceOnUse"><stop offset=".1" class="oepyb769y"/><stop offset=".26" class="mhnax-bah"/><stop offset=".56" class="nhg7phc8l"/><stop offset=".89" class="c1c9kfbgq"/></radialGradient><radialGradient id="SVG5RDvhbGU" cx="0" cy="0" r="1" gradientTransform="matrix(33.2458 0 0 69.2569 27.301 -23.622)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="mhnax-bah"/><stop offset=".56" class="nhg7phc8l"/><stop offset=".89" class="c1c9kfbgq"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zen" /></template>
<style>
.c1c9kfbgq {
  stop-color: var(--svg-color--0e9de5, #0e9de5);
}

.ft5dv1b6b {
  fill: none;
}

.lx_ophbum {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.24 11.75q1.16.001 2.293.25a4.524 4.524 0 0 0-7.93-2.979a4.5 4.5 0 0 0-1.07 3.587c-.625.46-1.193.99-1.694 1.582a6.56 6.56 0 0 1 5.331-8.67a6.53 6.53 0 0 1 3.77.636l2.276-1.477A8.985 8.985 0 0 0 3.022 11.37a9 9 0 0 0 1.742 5.986c.425-.767.94-1.48 1.535-2.122q.737-.762 1.588-1.392a10.75 10.75 0 0 1 6.359-2.09z");
}

.mhnax-bah {
  stop-color: var(--svg-color--23d29a, #23d29a);
}

.nhg7phc8l {
  stop-color: var(--svg-color--1abbbb, #1abbbb);
}

.oepyb769y {
  stop-color: var(--svg-color--26db8d, #26db8d);
}

.pgrs20b-l {
  d: path("M12.012 16.51a4.52 4.52 0 0 0 4.447-3.706a10.3 10.3 0 0 0-8.196 1.704a4.53 4.53 0 0 0 3.749 2.001");
}

.y962qp91i {
  d: path("m19.323 6.754l-1.472 2.28a6.562 6.562 0 0 1-4.796 9.432a6.54 6.54 0 0 1-3.987-.618l-2.287 1.47A8.986 8.986 0 0 0 20.97 12.73a9.03 9.03 0 0 0-1.647-5.98h.006z");
}

</style>
