<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGv9k1HeNI" cx="64" cy="-2048" r="56.96" fx="64" fy="-2048" gradientTransform="matrix(1 0 0 -1 0 -1984)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r_-r4-l8z"/><stop offset=".19" class="iod68mb-x"/><stop offset=".534" class="prs4pqm9g"/><stop offset=".991" class="vxbl1_bue"/><stop offset="1" class="wmt7xnpto"/></radialGradient><radialGradient id="SVGsiNypczI" cx="23.773" cy="84.475" r="23.261" fx="23.773" fy="84.475" gradientTransform="matrix(.97908 0 0 .93012 9.682 8.098)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="xxl2uvnsa"/><stop offset=".187" class="popcf8e5b"/><stop offset=".445" class="l8y_lcbgu"/><stop offset=".791" class="a44b3qwyn"/><stop offset=".935" class="he1ha19dv"/></radialGradient><radialGradient id="SVGiM8ARbfN" cx="87.217" cy="81.739" r="22.716" fx="87.217" fy="81.739" gradientTransform="matrix(.97908 0 0 .93012 9.682 6.938)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="xxl2uvnsa"/><stop offset=".197" class="popcf8e5b"/><stop offset=".474" class="l8y_lcbgu"/><stop offset=".845" class="a44b3qwyn"/><stop offset="1" class="he1ha19dv"/></radialGradient></defs><path fill="url(#SVGv9k1HeNI)" class="uuo0vn6ns"/><path class="fmeykjwqb"/><path fill="url(#SVGsiNypczI)" class="o4k7tq_sp"/><path fill="url(#SVGiM8ARbfN)" class="p91nq9nxc"/><path class="z58-lfy7e"/><path class="ec28kccfs"/><path class="ztngj_b5e"/><path class="b2kb73b6r"/><path class="osfc3m_xc"/><path class="i59zq1byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:nauseated-face" /></template>
<style>
.a44b3qwyn {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.098;
}

.b2kb73b6r {
  fill: var(--svg-color--83622f, #83622f);
  d: path("M45.9 48.1c-1-.7-2.6-.5-3.6 1s-.7 3 .4 3.7c1 .7 2.6.5 3.6-1c1-1.4.7-3-.4-3.7");
}

.ec28kccfs {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M28.785 44.3c-2 .9-1.4 4 1 3.6c5.2-1.2 9.7-4.3 12.6-8.8c1.1-1.6 2-3.4 2.5-5.3c.4-.9 0-2-1-2.4s-2 .1-2.4 1c-2.8 5.3-7.2 9.4-12.6 11.8h-.1zm57.7-11.5c-.4-.9-1.4-1.4-2.4-1c-.9.4-1.4 1.4-1 2.4c.5 1.9 1.4 3.7 2.5 5.3c2.9 4.4 7.4 7.5 12.6 8.7c2.5.5 3-2.7 1-3.6c-5.5-2.3-9.9-6.5-12.7-11.7");
}

.fmeykjwqb {
  fill: var(--svg-color--789e46, #789e46);
  d: path("M111.893 30.769C117.22 39.366 120 49.612 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.063 0-37.037-7.347-48.179-22.94C24.583 111.623 44.811 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.742-3.471-24.06-10.107-33.231");
}

.he1ha19dv {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0;
}

.i59zq1byo {
  fill: var(--svg-color--83622f, #83622f);
  d: path("M81.3 48.1c-1-.7-2.6-.5-3.6 1s-.7 3 .4 3.7c1 .7 2.6.5 3.6-1s.7-3-.4-3.7");
}

.iod68mb-x {
  stop-color: var(--svg-color--f0dd36, #f0dd36);
}

.l8y_lcbgu {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.314;
}

.o4k7tq_sp {
  d: path("M54.3 87.186c0 12.755-8.955 26.163-21.396 23.346c-12.805-2.9-25.22-22.15-22.98-31.968c1.955-8.562 8.524-14.475 21.28-14.475S54.3 74.43 54.3 87.186");
}

.osfc3m_xc {
  fill: var(--svg-color--3f2c13, #3f2c13);
  d: path("M81.7 44.2c-4.2 0-8 3.5-8 9.4s3.8 9.4 8 9.4s8-3.5 8-9.4s-3.8-9.4-8-9.4");
}

.p91nq9nxc {
  d: path("M116.462 79.692c0 12.756-12.946 26.251-22.476 26.251c-12.756 0-21.184-9.755-21.184-22.51s10.34-23.097 23.096-23.097s20.564 6.6 20.564 19.356");
}

.popcf8e5b {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.449;
}

.prs4pqm9g {
  stop-color: var(--svg-color--d0d648, #d0d648);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.vxbl1_bue {
  stop-color: var(--svg-color--9dcc64, #9dcc64);
}

.wmt7xnpto {
  stop-color: var(--svg-color--9ccc65, #9ccc65);
}

.xxl2uvnsa {
  stop-color: var(--svg-color--ff4747, #ff4747);
  stop-opacity: 0.5;
}

.z58-lfy7e {
  fill: none;
  stroke: var(--svg-color--35220b, #35220b);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--5-3px, 5.3px);
  d: path("M41.1 73.4c2.6 2 5.7 4.9 6.8 7.6c.9 2.2 1.1 4.5.6 6.8m38.4-15.1c-2.4 1.1-8.7 6.9-6.2 14.8m-32.8-7s3.7-4.8 16.2-5c11.3-.2 16 3.4 16 3.4");
}

.ztngj_b5e {
  fill: var(--svg-color--3f2c13, #3f2c13);
  d: path("M46.3 44.2c-4.2 0-8 3.5-8 9.4s3.8 9.4 8 9.4s8-3.5 8-9.4s-3.8-9.4-8-9.4");
}

</style>
