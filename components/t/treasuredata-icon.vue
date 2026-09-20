<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":174};
const content = `<defs><linearGradient id="SVG6BNOK6yg" x1="28.028%" x2="65.934%" y1="64.775%" y2="20.384%"><stop offset="0%" class="c3fcnjbse"/><stop offset="100%" class="i_nwpdb4a"/></linearGradient><linearGradient id="SVGxdW9eeFw" x1="49.198%" x2="57.126%" y1="50.864%" y2="43.347%"><stop offset="7%" class="vc--wpv5i"/><stop offset="89%" class="pd69vibey"/></linearGradient><linearGradient id="SVGXpOh9dPu" x1="19.368%" x2="129.609%" y1="222.565%" y2="308.848%"><stop offset="7%" class="vc--wpv5i"/><stop offset="89%" class="pd69vibey"/></linearGradient><linearGradient id="SVGyNkS5bzD" x1="11.015%" x2="75.43%" y1="39.462%" y2="63.266%"><stop offset="0%" class="d_fco1bvp"/><stop offset="98%" class="wlzn5acfz"/></linearGradient></defs><path fill="url(#SVG6BNOK6yg)" class="uk-jn-b3p"/><path fill="url(#SVGxdW9eeFw)" class="m7-jjxw-k"/><path fill="url(#SVGXpOh9dPu)" class="anyfq_bal"/><path fill="url(#SVGyNkS5bzD)" class="i734w4y3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:treasuredata-icon" /></template>
<style>
.anyfq_bal {
  d: path("m211.795 8.892l-11.68 23.73l49.79 10.066a6.156 6.156 0 0 1 4.789 7.244a5.7 5.7 0 0 1-.386 1.21a12.28 12.28 0 0 0-1.947-14.908L222.002 5.858A19.92 19.92 0 0 0 207.884 0h-1.543a6.103 6.103 0 0 1 5.454 8.874z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.c3fcnjbse {
  stop-color: var(--svg-color--85f, #85f);
}

.d_fco1bvp {
  stop-color: var(--svg-color--4036c1, #4036c1);
}

.i_nwpdb4a {
  stop-color: var(--svg-color--00b6ff, #00b6ff);
}

.i734w4y3k {
  d: path("M254.308 51.212a6.14 6.14 0 0 0-3.192-8.068a5.7 5.7 0 0 0-1.21-.385L200.114 32.62l-66.996 135.204a8.225 8.225 0 0 1-9.804 4.209a12.38 12.38 0 0 0 13.47-2.666L252.36 53.773a11.1 11.1 0 0 0 1.947-2.561");
}

.m7-jjxw-k {
  d: path("M33.22 6.787a17.54 17.54 0 0 1 15.977-4.805l200.709 40.706a6.156 6.156 0 0 1 4.788 7.244a5.7 5.7 0 0 1-.386 1.21a12.28 12.28 0 0 0-1.947-14.908L222.002 5.858A19.92 19.92 0 0 0 207.884 0h-159.6A20 20 0 0 0 34.15 5.858z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.pd69vibey {
  stop-color: var(--svg-color--009fff, #009fff);
}

.uk-jn-b3p {
  d: path("M136.783 169.368L252.361 53.773a12.38 12.38 0 0 0 0-17.539L222.002 5.858A19.92 19.92 0 0 0 207.884 0h-159.6A20 20 0 0 0 34.15 5.858L3.685 36.287A12.28 12.28 0 0 0 0 44.932a12.28 12.28 0 0 0 3.51 8.718l.175.175l115.578 115.596a12.38 12.38 0 0 0 17.538 0z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wlzn5acfz {
  stop-color: var(--svg-color--539eff, #539eff);
}

</style>
