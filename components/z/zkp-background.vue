<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="eeceg7byh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zkp-background" /></template>
<style>
.eeceg7byh {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16M5.882 8.452l-.08.023a7.144 7.144 0 1 1 6.212 10.664a2.695 2.695 0 0 1-2.198-4.25l.005-.01a2.683 2.683 0 0 1 3.558-.752l1.082 1.068c.127.188 1.19.127 1.379 0c.15-.094.141-.588.132-.79a.18.18 0 0 1 .06-.141c.142-.127.462-.41.56-.509c.095-.094.119-.437.123-.602c0-.052.029-.104.076-.141c.174-.141.254-.372.282-.494a.17.17 0 0 0-.019-.142l-.988-1.571a.18.18 0 0 1-.024-.123c.014-.127.01-.433-.329-.814c-.438-.503-2.57-1.694-2.88-1.755c-.235-.047-.574-.024-.73-.01a.17.17 0 0 1-.15-.051c-.212-.212-.904-.894-1.064-1.007c-.178-.118-.258-.047-.305 0h-.005q-.175.365-.226.767a.19.19 0 0 1-.202.155c-1.205-.122-3.21.254-4.264.485z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
