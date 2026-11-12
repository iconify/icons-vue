<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x9qq19fwj"/><path class="oy0yg19qw"/><path class="n09gebbpm"/><path class="y8zlfsl7g"/><path class="m49h4_eiq"/><path class="j61xww1jd"/><path class="le9iyfafr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toolbox-linear" /></template>
<style>
.j61xww1jd {
  stroke-linecap: round;
  d: path("M5.37839 11H8.40549C8.61447 11 8.78388 11.1694 8.78388 11.3784V13.0141C8.78388 13.1689 8.68968 13.308 8.54602 13.3655L8.01618 13.5774C7.29449 13.8661 6.4894 13.8661 5.7677 13.5774L5.23786 13.3655C5.0942 13.308 5 13.1689 5 13.0141V11.3784C5 11.1694 5.16941 11 5.37839 11Z");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.le9iyfafr {
  stroke-linecap: round;
  d: path("M15.3784 11H18.4055C18.6145 11 18.7839 11.1694 18.7839 11.3784V13.0141C18.7839 13.1689 18.6897 13.308 18.546 13.3655L18.0162 13.5774C17.2945 13.8661 16.4894 13.8661 15.7677 13.5774L15.2379 13.3655C15.0942 13.308 15 13.1689 15 13.0141V11.3784C15 11.1694 15.1694 11 15.3784 11Z");
}

.m49h4_eiq {
  stroke-linecap: round;
  d: path("M8.78388 12L14.9997 12");
}

.n09gebbpm {
  stroke-linecap: round;
  d: path("M2 12L5 12");
}

.oy0yg19qw {
  stroke-linecap: round;
  d: path("M16.52 6C16.52 4.11438 16.52 3.17157 15.9342 2.58579C15.3484 2 14.4056 2 12.52 2H11.4795C9.59387 2 8.65107 2 8.06528 2.58579C7.47949 3.17157 7.47949 4.11438 7.47949 6");
}

.x9qq19fwj {
  d: path("M22 12.0256V12.0256C22 9.18012 22 7.75736 21.1213 6.87868C20.2426 6 18.8284 6 16 6L8 6C5.17157 6 3.75736 6 2.87868 6.87868C2 7.75736 2 9.18012 2 12.0256V12.0256C2 14.8712 2 16.2939 2.87868 17.1726C3.75736 18.0513 5.17157 18.0513 8 18.0513L16 18.0513C18.8284 18.0513 20.2426 18.0513 21.1213 17.1726C22 16.2939 22 14.8712 22 12.0256Z");
}

.y8zlfsl7g {
  stroke-linecap: round;
  d: path("M18.7839 12L22 12");
}

</style>
