<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i11bk_b5x"/><path class="v9x8etbne"/><path class="rho-iid4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:reminder-ribbon" /></template>
<style>
.i11bk_b5x {
  fill: var(--svg-color--a5233c, #a5233c);
  d: path("M44.896 15.453s-7.477-7.143-25.19-.363l.29-9.699l.726-1.721s10.581-8.04 24.862.032l.734 11.771l-1.419-.02");
}

.rho-iid4d {
  fill: var(--svg-color--bc2a3f, #bc2a3f);
  d: path("M25.292 37.484L16.08 49.07l5.163 14.755l10.538-15.943zM45.67 3.783l-.143-.116a.4.4 0 0 1-.063-.021c.373 1.537.833 6.458-5.04 14.805l-7.03 8.846l6.395 8.469l6.301-9.531c-.001 0 7.429-8.142-.422-22.452");
}

.v9x8etbne {
  fill: var(--svg-color--df394c, #df394c);
  d: path("M25.34 18.223c-6.15-9.297-4.958-13.695-4.621-14.552q-.008 0-.01.004c-.01.016-.028.031-.042.043c-8.678 14.342-1.214 22.12-1.214 22.12l23.76 38.29L48.8 49.526l-23.46-31.3");
}

</style>
