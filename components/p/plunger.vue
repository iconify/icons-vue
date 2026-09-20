<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rloqhobaa"/><path class="m49i_013p"/><path class="ncfwtcbqr"/><path class="yw1h14bzn"/><path class="ydigm6-jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:plunger" /></template>
<style>
.m49i_013p {
  fill: var(--svg-color--dd637f, #dd637f);
  d: path("m15.009 24.848l-3.901-3.901a1.505 1.505 0 0 1 0-2.121l.298-.298a1.505 1.505 0 0 1 2.121 0l3.901 3.901a1.505 1.505 0 0 1 0 2.121l-.298.298a1.505 1.505 0 0 1-2.121 0");
}

.ncfwtcbqr {
  fill: var(--svg-color--dd637f, #dd637f);
  d: path("M2.95 22.466c3.118-3.118 8.004-3.286 10.915-.376s2.742 7.797-.376 10.915z");
}

.rloqhobaa {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M10.481 25.519a1.82 1.82 0 0 1 0-2.567L32.433 1A1.82 1.82 0 0 1 35 1a1.82 1.82 0 0 1 0 2.567L13.048 25.519a1.82 1.82 0 0 1-2.567 0");
}

.ydigm6-jl {
  fill: var(--svg-color--eb8caa, #eb8caa);
  d: path("M6 25c3-3 5.5-3.5 5.5-3.5S7 20 4 23z");
}

.yw1h14bzn {
  fill: var(--svg-color--bf345d, #bf345d);
  d: path("m11.922 34.664l-10.63-10.63a1.003 1.003 0 0 1 0-1.414l.199-.199a1.003 1.003 0 0 1 1.414 0l10.63 10.63a1.003 1.003 0 0 1 0 1.414l-.199.199a1.003 1.003 0 0 1-1.414 0m4.862-9.587l-5.905-5.905a1.47 1.47 0 0 0-.029 1.385l4.548 4.548c.441.223.952.211 1.386-.028");
}

</style>
