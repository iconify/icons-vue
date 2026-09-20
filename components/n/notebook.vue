<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="if-apcs_a"/><path class="llpo365nn"/><path class="l_m7g57lm"/><path class="eizfmxo9v"/><path class="qqjvve8hw"/><path class="lm0v_4bsy"/><path class="q6_gt5b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:notebook" /></template>
<style>
.eizfmxo9v {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M31 32a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V10a4 4 0 0 1 4-4h21a4 4 0 0 1 4 4z");
}

.if-apcs_a {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M35 26a4 4 0 0 1-4 4H5a4 4 0 0 1-4-4V6.313C1 4.104 6.791 0 9 0h20.625C32.719 0 35 2.312 35 5.375z");
}

.l_m7g57lm {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M31 31a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3z");
}

.llpo365nn {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M33 30a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V6c0-4.119-.021-4 5-4h21a4 4 0 0 1 4 4z");
}

.lm0v_4bsy {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M6 6C4.312 6 4.269 4.078 5 3.25C5.832 2.309 7.125 2 9.438 2H11V0H8.281C4.312 0 1 2.5 1 5.375V32a4 4 0 0 0 4 4h2V6z");
}

.q6_gt5b3g {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M7 8h3v4H7zm7 0h4v4h-4zm12 .056A5 5 0 0 0 25.335 8H22v4h4zM18 12h4v4h-4zm8 0h3v4h-3zm-16 0h4v4h-4zm-3 4h3v4H7zm7 0h4v4h-4zm8 0h4v4h-4zm-4 4h4v4h-4zm8 0h3v4h-3zm-16 0h4v4h-4zm-3 4h3v4H7zm7 0h4v4h-4zm8 0h4v4h-4zM7 32h3v4H7zm7 0h4v4h-4zm8 4h3c.347 0 .679-.058 1-.141V32h-4zm-4-8h4v4h-4zm8 0h3v4h-3zm-16 0h4v4h-4z");
}

.qqjvve8hw {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M29 32a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V12a4 4 0 0 1 4-4h19.335C27.544 8 29 9.456 29 11.665z");
}

</style>
