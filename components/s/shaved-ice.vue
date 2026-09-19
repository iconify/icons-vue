<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="translate(4)"><ellipse class="a7rtfblui"/><path class="i2mzibc1c"/><path class="gx8vpnxek"/><path class="pfc2vjbha"/><ellipse class="iwl-j3bfp"/><ellipse class="c5jkqab7d"/><path class="av4vdxbno"/><path class="o2ypomb4f"/><path class="ip3h1ubbk"/><path class="q6jpiu38h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:shaved-ice" /></template>
<style>
.a7rtfblui {
  cx: 29.11px;
  cy: 56.14px;
  fill: var(--svg-color--04a69c, #04a69c);
  rx: 28.25px;
  ry: 7.609px;
}

.av4vdxbno {
  fill: var(--svg-color--f5e8d9, #f5e8d9);
  d: path("M58.23 27.875c.189 8.673-14.85 10.506-29.799 10.837c-14.954.335-28.22-3.737-28.42-12.407c-.182-8.678 19.69-21.854 34.63-22.18c14.943-.326 23.398 15.09 23.589 23.755");
}

.c5jkqab7d {
  cx: 29.11px;
  cy: 28.405px;
  fill: var(--svg-color--04a69c, #04a69c);
  rx: 28.18px;
  ry: 8.319px;
}

.gx8vpnxek {
  fill: var(--svg-color--04a69c, #04a69c);
  d: path("M58.18 28.852c0-8.224-13.01-8.762-29.07-8.762S.04 20.628.04 28.852c0 8.212 13.01 28.48 29.07 28.48c16.07 0 29.07-20.269 29.07-28.48");
}

.i2mzibc1c {
  fill: var(--svg-color--0b7d70, #0b7d70);
  d: path("M51.716 56.14c0 3.362-10.12 6.088-22.605 6.088c-12.481 0-22.601-2.726-22.601-6.088c0-3.359 10.12-6.084 22.601-6.084c12.485 0 22.605 2.724 22.605 6.084");
}

.ip3h1ubbk {
  fill: var(--svg-color--eb77ab, #eb77ab);
  d: path("M54.17 17.189c.138 6.291-13.04 17.792-23.683 11.895c-11.04-6.12-23.54-6.634-23.681-12.919C6.673 9.87 22.866.274 35.026.005c12.157-.265 19.01 10.899 19.14 17.18");
}

.iwl-j3bfp {
  cx: 29.11px;
  cy: 27.608px;
  fill: var(--svg-color--bcbdbf, #bcbdbf);
  rx: 28.9px;
  ry: 9.116px;
}

.o2ypomb4f {
  fill: var(--svg-color--e9ddd6, #e9ddd6);
  d: path("M50.587 34.09c-8.326 2.216-19.524 2.02-27.564-1.303c-7.409-3.06-14.734-9.909-10.132-18.762c.926-1.785 2.086-3.295 3.396-4.626C7.187 14.101-.11 21.033.001 26.309c.195 8.67 13.467 12.742 28.418 12.407c12.73-.279 25.498-1.67 28.895-7.431c-1.948 1.172-4.156 2.119-6.727 2.805");
}

.pfc2vjbha {
  fill: var(--svg-color--089083, #089083);
  d: path("M24.352 44.54c-4.311-6.863-6.554-17.545-2.684-24.375C9.227 20.464.047 21.949.047 28.852c0 8.212 13.01 28.48 29.07 28.48c3.168 0 6.209-.797 9.06-2.122c-5.531-2.343-10.611-5.55-13.83-10.67");
}

.q6jpiu38h {
  fill: var(--svg-color--db7db2, #db7db2);
  d: path("M22.826 15.267c-1.918-5.971-.717-10.25 2.231-13.366c-9.522 3.16-18.352 9.61-18.254 14.264c.142 6.285 12.641 6.799 23.681 12.919c3.58 1.984 7.438 1.97 10.991.879c-6.923-2.941-16.376-7.63-18.649-14.696");
}

</style>
