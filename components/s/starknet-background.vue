<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ujvs5305h"/><path clip-rule="evenodd" class="ueuzo4b8r"/><path fill="url(#SVG5sLj9bwS)" clip-rule="evenodd" class="r764f8b9s"/><path clip-rule="evenodd" class="f850r83ay"/><path clip-rule="evenodd" class="e_f8ckunb"/></g><defs><linearGradient id="SVG5sLj9bwS" x1="22.202" x2="-16.341" y1="2.883" y2="13.996" gradientUnits="userSpaceOnUse"><stop class="l996otjri"/><stop offset="1" class="ag4da7bfb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:starknet-background" /></template>
<style>
.ag4da7bfb {
  stop-color: var(--svg-color--d672ef, #d672ef);
}

.e_f8ckunb {
  fill: var(--svg-color--ec796b, #ec796b);
  fill-rule: evenodd;
  d: path("M16.213 16.39a1.145 1.145 0 1 0 2.29 0a1.145 1.145 0 0 0-2.29 0");
}

.f850r83ay {
  fill: var(--svg-color--fafafa, #fafafa);
  fill-rule: evenodd;
  d: path("M20 9.237c-.341-.861-.975-1.586-1.827-2.12a4.5 4.5 0 0 0-3.186-.57a5.2 5.2 0 0 0-1.621.611a6.8 6.8 0 0 0-1.301.994c-.19.184-.36.376-.53.569l-.44.562l-.682.904c-.867 1.164-1.802 2.528-3.336 2.932c-1.505.397-2.158.046-3.077-.1c.168.434.376.855.658 1.226c.277.378.604.733 1.01 1.037c.206.147.423.29.664.413c.24.119.499.223.775.3a4.5 4.5 0 0 0 1.766.123a5.3 5.3 0 0 0 1.672-.521a7 7 0 0 0 1.335-.875a10.7 10.7 0 0 0 1.898-2.086c.257-.361.49-.73.707-1.098l.255-.438c.078-.128.156-.257.236-.377c.323-.483.638-.87 1.021-1.16c.378-.298.904-.519 1.607-.57c.7-.052 1.508.044 2.396.244");
}

.ft5dv1b6b {
  fill: none;
}

.l996otjri {
  stop-color: var(--svg-color--ec796b, #ec796b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r764f8b9s {
  fill-rule: evenodd;
  d: path("M20 9.237c-.318-.355-.813-.555-1.295-.637a4.5 4.5 0 0 0-1.475.014c-.97.164-1.851.566-2.62 1.061c-.4.243-.74.525-1.092.811c-.17.145-.325.3-.486.452l-.441.438c-.48.501-.952.957-1.409 1.335c-.458.377-.887.663-1.31.862a3.5 3.5 0 0 1-1.463.338c-.584.02-1.275-.085-2.014-.26c-.743-.172-1.523-.419-2.395-.631c.304.843.762 1.59 1.35 2.271c.595.67 1.338 1.28 2.293 1.682a5.55 5.55 0 0 0 3.228.335c1.108-.213 2.081-.726 2.867-1.319a10.2 10.2 0 0 0 1.964-1.991c.148-.196.226-.306.334-.46l.297-.439c.206-.272.394-.581.598-.85c.4-.565.795-1.129 1.253-1.648c.231-.264.475-.515.762-.758q.213-.179.47-.338c.174-.112.357-.2.584-.268");
}

.ueuzo4b8r {
  fill: var(--svg-color--fafafa, #fafafa);
  fill-rule: evenodd;
  d: path("m7.824 9.683l.248-.766a.5.5 0 0 1 .33-.325l.77-.237c.107-.033.107-.183.002-.218l-.767-.248a.5.5 0 0 1-.325-.33l-.237-.77c-.032-.106-.183-.108-.217-.002l-.248.767a.5.5 0 0 1-.33.325l-.77.237a.114.114 0 0 0-.002.217l.767.248c.155.05.276.174.325.33l.236.77a.114.114 0 0 0 .218.002");
}

.ujvs5305h {
  fill: var(--svg-color--0c0c4f, #0c0c4f);
  d: path("M24 0H0v24h24z");
}

</style>
