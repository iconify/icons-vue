<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="v2y8xibsw"/><path clip-rule="evenodd" class="ap-nihr8h"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:neon-evm-background" /></template>
<style>
.ap-nihr8h {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20c4.418 0 8-3.58 8-7.994C20.011 7.579 16.418 4 12 4s-8 3.58-8 7.994C4 16.41 7.582 20 12 20M8.904 8.596l2.994 2.992V8.754c0-.023 0-.057.012-.08a.2.2 0 0 1 .113-.112c.022-.012.056-.012.079-.012h3.389c.023 0 .057.012.08.012a.2.2 0 0 1 .067.045a.2.2 0 0 1 .046.068a.2.2 0 0 1 .01.079v6.729c0 .034 0 .057-.01.08c-.012.022-.023.045-.046.067a.2.2 0 0 1-.068.045a.2.2 0 0 1-.079.012c-.033 0-.056 0-.09-.012c-.022-.01-.056-.022-.068-.045l-2.994-2.992v2.845c0 .023 0 .057-.011.08c-.012.022-.023.045-.045.067a.2.2 0 0 1-.068.045c-.023.012-.057.012-.08.012H8.747c-.023 0-.057-.012-.08-.012a.2.2 0 0 1-.067-.045a.2.2 0 0 1-.045-.068c-.012-.022-.012-.056-.012-.079v-3.365c0-.022 0-.033.012-.056V8.754c0-.045.01-.08.034-.125a.18.18 0 0 1 .101-.079a.23.23 0 0 1 .125-.01c.022.01.067.033.09.056");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.v2y8xibsw {
  fill: var(--svg-color--df42ab, #df42ab);
  d: path("M24 0H0v24h24z");
}

</style>
