<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k9edmib-w"/><path clip-rule="evenodd" class="bbrh_wtok"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:stacks-background" /></template>
<style>
.bbrh_wtok {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.85 9.24a.32.32 0 0 1 .018-.338L17.793 4.6a.37.37 0 0 0 .018-.391a.38.38 0 0 0-.342-.2h-1.138a.4.4 0 0 0-.324.174l-3.416 5.04a.45.45 0 0 1-.385.2h-.43a.47.47 0 0 1-.385-.2l-3.398-5.05A.39.39 0 0 0 7.67 4H6.531a.38.38 0 0 0-.342.209a.39.39 0 0 0 .018.39L9.132 8.91a.3.3 0 0 1 .017.33a.32.32 0 0 1-.289.174H4.385A.38.38 0 0 0 4 9.797v.938c0 .218.175.383.385.383h15.23a.38.38 0 0 0 .385-.383v-.938c0-.2-.149-.356-.341-.383H15.14a.31.31 0 0 1-.29-.173m-3.45 5.537l-3.415 5.04a.39.39 0 0 1-.324.174H6.522a.4.4 0 0 1-.341-.2a.37.37 0 0 1 .017-.39l2.916-4.303a.32.32 0 0 0 .018-.339a.34.34 0 0 0-.29-.173H4.386A.38.38 0 0 1 4 14.203v-.938a.38.38 0 0 1 .385-.383h15.23c.21 0 .385.165.385.383v.938a.38.38 0 0 1-.385.383h-4.467a.3.3 0 0 0-.289.173a.3.3 0 0 0 .018.33l2.925 4.311a.39.39 0 0 1-.324.6h-1.139a.37.37 0 0 1-.315-.165l-3.415-5.04a.45.45 0 0 0-.386-.2h-.429a.47.47 0 0 0-.385.2z");
}

.ft5dv1b6b {
  fill: none;
}

.k9edmib-w {
  fill: var(--svg-color--fc6432, #fc6432);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
