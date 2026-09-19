<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bvg6u7zwv"/><ellipse class="ria0xwaac"/><g class="i1p719but"><ellipse class="v28iqy_6r"/><path class="gr07u588c"/></g><path class="mrii-jbbr"/><path class="xz9t1wc4m"/><path class="d4715lbbz"/><g class="n5udk-meq"><path class="izeicjbzg"/><path class="tm4jrfznv"/></g><path class="fs0_4drwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:top-hat" /></template>
<style>
.bvg6u7zwv {
  fill: var(--svg-color--323232, #323232);
  d: path("M63.53 55.43v2.057l-2.048.963s-.966-1.574-.942-1.992c.028-.414.251-1.539.414-1.461c.158.071 2.576.433 2.576.433M.86 55.15l-.032 2.5l1.392.281s.397-2.414.337-2.496c-.059-.08-.651-.506-.651-.506z");
}

.d4715lbbz {
  fill: var(--svg-color--577482, #577482);
  d: path("M56.02 9.3c0 2.779-10.667 5.03-23.825 5.03S8.371 12.083 8.371 9.3s10.666-5.03 23.824-5.03S56.02 6.518 56.02 9.3");
}

.fs0_4drwb {
  fill: var(--svg-color--243438, #243438);
  d: path("M32.2 4.273c-3.299 0-6.443.143-9.304.398c12.765.686 20.09 9.09 20.11 9.109c7.726-.832 13.02-2.523 13.02-4.479c0-2.78-10.667-5.03-23.825-5.03");
}

.gr07u588c {
  d: path("M8.374 9.3L9.89 55.4l45.21 1.06l.92-47.16l-26.52-.754z");
}

.i1p719but {
  fill: var(--svg-color--3b525e, #3b525e);
}

.izeicjbzg {
  d: path("M55.34 53.32c0 2.301-10.181 4.166-22.735 4.166c-12.558 0-22.735-1.865-22.735-4.166c0-2.307 10.177-4.172 22.735-4.172c12.554 0 22.735 1.866 22.735 4.172");
}

.mrii-jbbr {
  fill: var(--svg-color--243438, #243438);
  d: path("M47.01 56.27a3.4 3.4 0 0 1 1.326-1.1c1.85-.84 3.688-1.699 5.367-2.85a4.1 4.1 0 0 1 1.49-.619l.835-42.4l-26.523-.754l-5.729.203l19.337.551l-.921 46.856z");
}

.n5udk-meq {
  fill: var(--svg-color--fbb03b, #fbb03b);
}

.ria0xwaac {
  cx: 32px;
  cy: 55.43px;
  fill: var(--svg-color--577482, #577482);
  rx: 31.534px;
  ry: 6.285px;
}

.tm4jrfznv {
  d: path("M9.498 43.514s18.984 7.721 45.845 0v9.807l-19.748 1.672L9.873 53.32z");
}

.v28iqy_6r {
  cx: 32px;
  cy: 57.49px;
  rx: 31.534px;
  ry: 6.285px;
}

.xz9t1wc4m {
  fill: var(--svg-color--7196a8, #7196a8);
  d: path("m21.259 11.239l-7.643.053l1.359 37.2l7.469.229z");
}

</style>
