<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="utbsidbos"/><path clip-rule="evenodd" class="e20t2ih7u"/><path class="tyuz35pao"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wlkn-background" /></template>
<style>
.e20t2ih7u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 18.588a6.588 6.588 0 1 0 0-13.176a6.588 6.588 0 0 0 0 13.176M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tyuz35pao {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.47 11.021c-.376 0-.625.339-.705.508v2.588c0 .942.94 2.118 2.353 2.118c1.13 0 1.647-.47 1.882-.941c.235.47 1.096.941 1.647.941c1.647 0 2.588-1.176 2.588-1.99V9.68c0-.165-.141-.504-.706-.504c-.564 0-.706.34-.706.509v4.197c0 .339-.235.941-1.176.941s-.941-.602-.941-.94v-3.257c0-.17-.141-.508-.706-.508s-.706.338-.706.508v3.256c0 .339-.424.941-1.176.941c-.753 0-.942-.602-.942-.94v-2.354c0-.254-.235-.508-.705-.508");
}

.utbsidbos {
  fill: var(--svg-color--ffb830, #ffb830);
  d: path("M24 0H0v24h24z");
}

</style>
