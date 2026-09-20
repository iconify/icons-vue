<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ium9u-b_c"/><path clip-rule="evenodd" class="kq_fvmbmp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:status-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ium9u-b_c {
  fill: var(--svg-color--7140fd, #7140fd);
  d: path("M0 0h24v24H0z");
}

.kq_fvmbmp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.557 6.05a4 4 0 0 0-.396.718q-.078.18-.14.354c-.147.403-.239.77-.331 1.14l-.004.016c-.118.467-.236.935-.467 1.476a4.3 4.3 0 0 1-.428.77l-.004.006l-.002.004c2.067.598 4.377-.197 5.216-2.146c.516-1.197.229-2.696-.935-3.213c-.937-.417-1.856-.075-2.508.875zM4.163 12.02q.131-.39.338-.747q.1-.17.2-.323c.234-.358.472-.65.711-.942l.023-.028c.298-.366.597-.734.887-1.237a4.3 4.3 0 0 0 .364-.815c1.687 1.358 2.409 3.733 1.352 5.567c-.649 1.128-2.007 1.77-3.1 1.11c-.88-.53-1.147-1.49-.775-2.585M20 16.594c-2.23 0-4.04-1.844-4.04-4.119h-2.358C13.602 16.08 16.466 19 20 19zm-7.7-4.119C12.3 16.08 9.434 19 5.9 19v-2.406c2.23 0 4.04-1.844 4.04-4.119zm0 0l-.002-7.283h-2.36l.002 7.283z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
