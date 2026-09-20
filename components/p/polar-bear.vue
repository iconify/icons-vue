<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ttmu-t63i"/><path class="ed0m25t6t"/><path class="ycakq5c-a"/><path class="k4ffkccjh"/><path class="d2ke1yyaq"/><path class="znjt-hi3f"/><path class="e8a6erb2k"/><path class="gy1risd1f"/><circle class="xlaum6ncl"/><circle class="t7kzoibox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:polar-bear" /></template>
<style>
.d2ke1yyaq {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--91bdce, #91bdce);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M99.894 25.374C90.46 15.83 82.425 13.745 78.207 13.546c-5.885-.277-9.3 2.252-13.351 2.252c-.306 0-.586-.003-.856-.007c-.27.004-.55.007-.856.007c-4.051 0-7.466-2.53-13.35-2.252c-4.22.199-12.255 2.284-21.688 11.828c-11.7 11.838-21.998 29.444-21.998 50.825c0 12.27 4.639 21.096 11.631 26.818c11.908 9.743 29.368 13.059 46.13 13.059l.131-.002l.13.002c16.763 0 34.223-3.316 46.13-13.06c6.993-5.721 11.632-14.547 11.632-26.817c0-21.381-10.297-38.987-21.998-50.825z");
}

.e8a6erb2k {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M77.75 78c-1.394-1.053-3.912-2.458-7.202-3.676c-1.92-.714-3.338-2.341-3.244-4.379c.105-2.26.187-4.706.07-4.964c-.28-.62-2.002-1.065-2.857-.995h-.281c-.855-.07-2.588.375-2.858.995c-.093.223-.046 2.096.035 4.063c.106 2.459-1.498 4.53-3.782 5.444c-2.951 1.171-5.317 2.53-6.616 3.524c-.797.598-1.43 1.757-1.043 2.799c.504 1.334 2.74 1.147 4.005.573c3.396-1.545 6.523-2.353 10.4-2.353c3.887 0 7.002.808 10.398 2.353c1.265.574 3.502.761 4.005-.573c.398-1.054-.234-2.213-1.03-2.81");
}

.ed0m25t6t {
  fill: var(--svg-color--91bdce, #91bdce);
  d: path("M21.88 44.508S15.815 32.57 14.665 28.08c-.84-3.265.28-6.26 3.833-4.292c6.187 3.433 14.769 8.387 14.769 8.387z");
}

.gy1risd1f {
  fill: var(--svg-color--231f20, #231f20);
  d: path("M72.062 51.282c-3.478-2.19-11.184-2.095-15.645 0c-2.132.996-7.003 5.995-5.621 11.334c.597 2.318 2.248 4.18 3.97 5.222c2.12 1.276 8.782 2.927 9.473 2.915c.691.012 7.647-1.932 9.767-3.208c1.721-1.042 3.372-2.903 3.97-5.222c1.393-5.327-3.923-9.788-5.914-11.04");
}

.k4ffkccjh {
  fill: var(--svg-color--91bdce, #91bdce);
  d: path("M92.996 32.24s9.183-5.02 15.799-8.494c3.8-1.992 4.91 1.198 3.943 4.625c-1.324 4.712-8.02 17.17-8.02 17.17z");
}

.t7kzoibox {
  cx: 37.117px;
  cy: 46.546px;
  r: 5.176px;
  fill: var(--svg-color--231f20, #231f20);
}

.ttmu-t63i {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--91bdce, #91bdce);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M16.131 47.6S6.762 39.187 5.589 27.225s6.607-17.004 16.657-13.665s16.345 8.827 16.345 8.827z");
}

.xlaum6ncl {
  cx: 91.641px;
  cy: 46.546px;
  r: 5.176px;
  fill: var(--svg-color--231f20, #231f20);
}

.ycakq5c-a {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--91bdce, #91bdce);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M87.614 21.773s6.78-5.64 17.474-8.92s18.784 2.235 17.253 14.836s-11.63 21.258-11.63 21.258z");
}

.znjt-hi3f {
  fill: var(--svg-color--cfd8dc, #cfd8dc);
  d: path("M87.723 60.657c-6.51-17.128-18.865-19.24-23.35-19.24s-16.84 2.112-23.35 19.24c-3.479 9.156-5.704 16.212-4.275 23.305c2.834 14.125 13.935 18.917 27.636 18.917s24.803-4.804 27.637-18.917c1.405-7.093-.808-14.149-4.298-23.305");
}

</style>
