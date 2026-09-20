<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ky9rzsmgs"/><path class="ekf3xhn2x"/><path class="jnc-eybgh"/><path class="zpzn9-brj"/><circle class="uzpop4bzs"/><path class="jh70albcf"/><circle class="cdbeutbxd"/><path class="jhtm0mb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:rabbit" /></template>
<style>
.cdbeutbxd {
  cx: 6px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--292f33, #292f33);
}

.ekf3xhn2x {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M9.55 11.704c0-3.414-1.297-9.065-.648-9.065s4.538 3.296 3.241 9.065C11.405 14.986 11.562 15 10.846 15s-1.296.117-1.296-3.296");
}

.jh70albcf {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M30.733 31.736C32.227 30.354 33 28.218 33 25c0-7.18-6.82-11-14-11c-2.057 0-3.829.157-5.323.54C12.592 13.41 10.817 13 8.4 13C4.136 13 0 17.069 0 21.333c0 4.13 3.88 4.637 7.999 4.664L8 26c3 5 1 10 3 10c1.588 0 1.914-2.217 1.981-4.375a15 15 0 0 0 3.531 1.577C15.635 33.726 15 34.271 15 34.5c0 1.381 2 1.5 5 1.5c5.522 0 13 0 11-4a.7.7 0 0 0-.267-.264");
}

.jhtm0mb2m {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M2 21c0 1.104-.5 2-1 2s-1-.896-1-2s.448-1 1-1s1-.104 1 1");
}

.jnc-eybgh {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M4.789 12.375C3.726 8.372.033 2.256 1 2c.966-.257 7.792 2.07 7.655 9.349c-.078 4.142.161 4.096-.907 4.379s-1.897.65-2.959-3.353");
}

.ky9rzsmgs {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M9 11C9 6.858 7 0 8 0s7 4 5 11c-1.138 3.983-.896 4-2 4s-2 .142-2-4");
}

.uzpop4bzs {
  cx: 32.5px;
  cy: 28.5px;
  r: 3.5px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.zpzn9-brj {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M5.5 12.914c-.875-3.299-3.579-8.429-2.952-8.595s5.232 2.022 5.458 7.93c.129 3.361.285 3.335-.407 3.519c-.692.183-1.223.445-2.099-2.854");
}

</style>
