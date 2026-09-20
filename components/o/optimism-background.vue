<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="en6va-rjv"/><path clip-rule="evenodd" class="a6_yepa-k"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:optimism-background" /></template>
<style>
.a6_yepa-k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.859 15.378q.87.622 2.233.622q1.647 0 2.633-.745q.984-.754 1.385-2.277q.24-.933.413-1.923q.056-.353.056-.59q0-.776-.4-1.331a2.4 2.4 0 0 0-1.1-.845Q9.381 7.999 8.5 8q-3.238 0-4.018 3.055a36 36 0 0 0-.423 1.923a4 4 0 0 0-.058.6q0 1.166.859 1.8m4.133-2.467c-.22.851-.824 1.405-1.74 1.405c-.907 0-1.216-.613-1.053-1.405q.206-1.078.412-1.822c.236-.919.792-1.405 1.74-1.405c.903 0 1.198.605 1.042 1.405a26 26 0 0 1-.401 1.822m3.469 3.01a.24.24 0 0 0 .19.078h1.514a.33.33 0 0 0 .212-.079a.33.33 0 0 0 .122-.206l.479-2.24h1.54c.973 0 1.733-.471 2.29-.891q.848-.63 1.125-1.943q.068-.309.067-.595q0-.992-.756-1.52Q18.496 8 17.26 8h-2.962a.33.33 0 0 0-.212.08a.33.33 0 0 0-.122.206l-1.538 7.428a.28.28 0 0 0 .034.206m5.413-5.304c-.14.612-.673 1.172-1.3 1.172h-1.28l.441-2.105h1.336c.455 0 .835.09.835.59q0 .148-.032.343");
}

.en6va-rjv {
  fill: var(--svg-color--fe0420, #fe0420);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
