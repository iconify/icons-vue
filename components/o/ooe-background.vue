<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="zlpyhdb1o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ooe-background" /></template>
<style>
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

.zlpyhdb1o {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.204 12.497q.025-.358.014-.716c.578-.036 1.284-.222 1.67-.347A.16.16 0 0 0 20 11.28V9.932a.18.18 0 0 0-.144-.167a.2.2 0 0 0-.078.003a9 9 0 0 1-1.818.302h-.005a7.111 7.111 0 1 0-.088 4.151l.093.009c.613.022 1.48-.204 1.929-.356a.16.16 0 0 0 .111-.15v-1.347a.18.18 0 0 0-.222-.165a8.5 8.5 0 0 1-1.574.28zm-1.768-.16a5.4 5.4 0 0 0-.014-.823l-.253-.053c-.907-.2-1.867-.409-2.307-.373c-.418.035-1.182.222-1.653.346a.165.165 0 0 1-.21-.16V9.812c0-.071.045-.133.107-.151c.374-.129 1.112-.32 1.756-.32c.391 0 .969.151 1.609.311l.489.129a5.333 5.333 0 1 0 .142 4.111c-.889-.195-1.809-.395-2.24-.355c-.418.03-1.182.217-1.653.342a.165.165 0 0 1-.21-.16v-1.462c0-.072.045-.134.107-.152c.374-.128 1.112-.32 1.756-.32c.391 0 .969.152 1.609.312c.311.088.64.168.965.24");
}

</style>
