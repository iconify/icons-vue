<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":247};
const content = `<defs><radialGradient id="SVG0PSzkcNZ" cx="78.764%" cy="37.848%" r="89.873%" fx="78.764%" fy="37.848%"><stop offset="0%" class="cfu_gubcr"/><stop offset="100%" class="j-uhf078n"/></radialGradient><radialGradient id="SVGRj6oidNY" cx="68.739%" cy="4.398%" r="81.728%" fx="68.739%" fy="4.398%"><stop offset="0%" class="dw7_lym_o"/><stop offset="29.175%" class="g9ofnyb-m"/><stop offset="100%" class="cfu_gubcr"/></radialGradient><linearGradient id="SVGkwduYc4f" x1="18.239%" x2="81.159%" y1="0%" y2="84.337%"><stop offset="0%" class="l45y-8r5k"/><stop offset="66.971%" class="i66tu2bvc"/><stop offset="82.715%" class="sqo040b_p"/><stop offset="100%" class="gv7xgwudo"/></linearGradient><linearGradient id="SVGzhs2YbDy" x1="64.906%" x2="44.29%" y1="71.559%" y2="50%"><stop offset="0%" class="y72xaystu"/><stop offset="40.035%" class="ohjffrb3n"/><stop offset="64.9%" class="ghlecgmks"/><stop offset="100%" class="xmbnrxb0s"/></linearGradient></defs><path class="mdd09bblj"/><path fill="url(#SVG0PSzkcNZ)" class="se_cczb_j"/><path fill="url(#SVGRj6oidNY)" class="m9n7rkxmh"/><path fill="url(#SVGkwduYc4f)" class="vyh7xacoz"/><path fill="url(#SVGzhs2YbDy)" class="stiscfbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:reactivex" /></template>
<style>
.cfu_gubcr {
  stop-color: var(--svg-color--f80090, #f80090);
}

.dw7_lym_o {
  stop-color: var(--svg-color--57008e, #57008e);
}

.g9ofnyb-m {
  stop-color: var(--svg-color--5c008e, #5c008e);
}

.ghlecgmks {
  stop-color: var(--svg-color--f60090, #f60090);
  stop-opacity: 0.892;
}

.gv7xgwudo {
  stop-color: var(--svg-color--c10090, #c10090);
  stop-opacity: 0;
}

.i66tu2bvc {
  stop-color: var(--svg-color--e50090, #e50090);
}

.j-uhf078n {
  stop-color: var(--svg-color--4d008e, #4d008e);
}

.l45y-8r5k {
  stop-color: var(--svg-color--f70090, #f70090);
}

.m9n7rkxmh {
  d: path("M187.459 171.493c15.18 1.645 29.59-1.998 42.943-12.883c-20.174 22.503-45.4 33.817-74.343 36.895c13.82 11.749 27.147 17.041 39.896 14.776c-35.426 9.776-65.107-.984-101.213-36.94c-1.89 9.679 8.333 24.76 18.87 34.386c-61.138-26.505-66.498-109.073 8.053-129.383c-77.28-37.13-120.979 35.014-99.51 94.142c21.007 45.54 76.985 80.6 138.337 72.89c29.8-3.65 74.302-24.197 92.482-72.89c-12.813 11.498-35.716 21.512-45.936 22.28c34.59-17.287 53.264-46.662 48.022-86.81c-7.165 17.058-16.619 30.159-28.444 39.156c25.12-39.157 20.81-59.396 2.217-81.639c13.298 36.572-3.905 77.161-41.374 106.02");
}

.mdd09bblj {
  fill: var(--svg-color--ff0090, #ff0090);
  d: path("M16.685 157.125C3.567 87.38 38.236 20.115 117.81 11.166C106.836-.559 91.845-.647 84.949.78C72.77 4.66 73.152 12.541 59.338 22.72c-13.733 7.843-20.63 1.837-30.633 9.968c-9.983 8.07-3.017 26.597-7.204 30.2c-4.156 7.203-17.047 13.62-19.394 22.718c-1.94 11.636 5.264 19.948 4.987 29.922c.832 8.311-8.274 13.011-6.966 19.748c3.919 11.005 11.472 17.629 15.033 20.682c.816.576 1.678 1.993 1.523 1.167");
}

.ohjffrb3n {
  stop-color: var(--svg-color--f70090, #f70090);
  stop-opacity: 0.4;
}

.se_cczb_j {
  d: path("M158.275 60.579a5.264 5.264 0 1 1 .001-10.53a5.264 5.264 0 0 1 0 10.53M19.757 164.733C7.15 104.117 46.16 53.468 121.704 78.403c44.327 25.932 100.09 24.243 102.603 7.48c6.207-20.095-28.26-61.506-79.792-72.311C42.281-6.377-12.834 104.117 19.757 164.732");
}

.sqo040b_p {
  stop-color: var(--svg-color--d6008f, #d6008f);
  stop-opacity: 0.2;
}

.stiscfbof {
  d: path("M114.601 57.851s3.768-5.562 5.235-8.07c1.798-3.074 4.558-8.676 4.558-8.676S95.39 31.642 88.272 30.487c-22.127 5.744-22.207 15.014-9.837 29.203c1.376 1.58 36.166-1.839 36.166-1.839");
}

.vyh7xacoz {
  d: path("M169.707 213.626c-2.625-.49 5.95 3.473-10.628-.916c-16.577-4.388-33.456-8.617-64.337-39.37c-1.89 9.68 8.333 24.76 18.87 34.387c28.444 19.838 9.1 10.56 52.44 25.542c3.478-6.922 3.655-13.074 3.655-19.643");
}

.xmbnrxb0s {
  stop-color: var(--svg-color--ff0090, #ff0090);
}

.y72xaystu {
  stop-color: var(--svg-color--b2008f, #b2008f);
  stop-opacity: 0.151;
}

</style>
