<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="d9ceq_boi"/><path class="doix3bb7j"/><path class="t-_7j6rku"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:newo-background" /></template>
<style>
.d9ceq_boi {
  fill: var(--svg-color--ea4e8c, #ea4e8c);
  d: path("M11.992 16.427c3.265 0 5.912-2.392 5.912-5.343S15.257 5.74 11.992 5.74S6.08 8.133 6.08 11.084s2.647 5.343 5.912 5.343");
}

.doix3bb7j {
  fill: var(--svg-color--fdfe5d, #fdfe5d);
  d: path("M15.259 4.94a6 6 0 0 0-.712-.387v11.633c.245-.111.485-.245.711-.387zM16 15.252q.388-.334.715-.729V6.211A7 7 0 0 0 16 5.486zm-5.828-10.98c.231-.07.471-.128.711-.177v12.544a6 6 0 0 1-.71-.178zM12 16.747c-.124 0-.249 0-.373-.013V4.01q.36-.022.72 0v12.722L12 16.74zm1.085-.098a5 5 0 0 0 .72-.178V4.273a7 7 0 0 0-.72-.178zM7.257 6.246q.331-.393.716-.733v9.722a6 6 0 0 1-.716-.734V6.242zm2.178 9.935a6 6 0 0 1-.72-.395V4.957q.342-.22.716-.395v11.615zm8.024-2.742a6.5 6.5 0 0 0 .764-3.067a6.45 6.45 0 0 0-.764-3.063zM5.777 10.367a6.5 6.5 0 0 1 .738-3.014v6.032a6.46 6.46 0 0 1-.738-3.018");
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

.t-_7j6rku {
  fill: var(--svg-color--e85ef5, #e85ef5);
  d: path("M9.43 7.834q.36-.172.748-.29v12.19a6 6 0 0 1-.747-.29zM11.632 20a7 7 0 0 1-.742-.089V7.362q.364-.067.742-.089zm.711 0a6 6 0 0 0 .747-.089V7.362a7 7 0 0 0-.742-.089V20zm2.92-.933c.259-.165.508-.352.743-.552V8.763a6 6 0 0 0-.742-.552zm-.71.386V7.82a6 6 0 0 0-.747-.289v12.202c.253-.08.502-.178.742-.284zM6.51 10.621q.315-.6.743-1.112v8.255a6 6 0 0 1-.743-1.111zm2.2-2.4a7 7 0 0 0-.742.555v9.721c.236.205.48.387.743.556zm8.758 8.476a6.3 6.3 0 0 1-.747 1.098V9.483q.426.513.747 1.102z");
}

</style>
