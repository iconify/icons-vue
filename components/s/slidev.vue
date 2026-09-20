<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGV1mLkeHH" x1="0%" x2="100%" y1="-8.889%" y2="100%"><stop offset="0%" class="kak-3_bpv"/><stop offset="100%" class="neg8bybfm"/></linearGradient><linearGradient id="SVGftQg8dYh" x1="-10.556%" x2="84.536%" y1="-12.222%" y2="100%"><stop offset="0%" class="agid22ysu"/><stop offset="100%" class="p0zws5bzc"/></linearGradient><linearGradient id="SVGVVA97yWc" x1="-.132%" x2="12.361%" y1="-8.073%" y2="104.495%"><stop offset="0%" class="zst8hxkht"/><stop offset=".01%" class="zst8hxkht"/><stop offset="8.333%" class="g42qkjuof"/><stop offset="60.177%" class="wo4-_c9pq"/><stop offset="100%" class="bgjt_ibpq"/></linearGradient></defs><path fill="url(#SVGV1mLkeHH)" class="l8bogdvxz"/><path fill="url(#SVGftQg8dYh)" class="lf5q7_baj"/><path fill="url(#SVGVVA97yWc)" class="rggya-xog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:slidev" /></template>
<style>
.agid22ysu {
  stop-color: var(--svg-color--95f0cf, #95f0cf);
}

.bgjt_ibpq {
  stop-color: var(--svg-color--ffa800, #ffa800);
}

.g42qkjuof {
  stop-color: var(--svg-color--ffdd35, #ffdd35);
}

.kak-3_bpv {
  stop-color: var(--svg-color--3acbd4, #3acbd4);
}

.l8bogdvxz {
  d: path("M71.385 34.462h147.692c20.392 0 36.923 16.53 36.923 36.923v147.692C256 239.469 239.469 256 219.077 256H71.385c-20.392 0-36.923-16.531-36.923-36.923V71.385c0-20.392 16.53-36.923 36.923-36.923");
}

.lf5q7_baj {
  d: path("M110.77 0c61.175 0 110.768 49.593 110.768 110.77c0 61.175-49.593 110.768-110.769 110.768S0 171.945 0 110.77S49.593 0 110.77 0");
}

.neg8bybfm {
  stop-color: var(--svg-color--2988b1, #2988b1);
}

.p0zws5bzc {
  stop-color: var(--svg-color--3ab9d5, #3ab9d5);
}

.rggya-xog {
  d: path("M138.159 157.354c-2.897-10.812-4.346-16.218-2.912-19.951a12.3 12.3 0 0 1 7.079-7.08c3.733-1.433 9.14.016 19.95 2.913l53.74 14.399c10.811 2.897 16.217 4.345 18.734 7.453a12.3 12.3 0 0 1 2.59 9.671c-.625 3.95-4.582 7.907-12.497 15.822l-39.34 39.34c-7.914 7.914-11.871 11.871-15.821 12.497a12.3 12.3 0 0 1-9.67-2.592c-3.109-2.516-4.557-7.922-7.454-18.734z");
}

.wo4-_c9pq {
  stop-color: var(--svg-color--ffbb13, #ffbb13);
}

.zst8hxkht {
  stop-color: var(--svg-color--ffeb83, #ffeb83);
}

</style>
