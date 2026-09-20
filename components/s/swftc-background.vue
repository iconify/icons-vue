<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="oba78abop"/><path class="i0kydnbit"/><path class="w1qt675ia"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:swftc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i0kydnbit {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.694 7.2a2.15 2.15 0 0 1 1.708.832c-.672.12-.8.736-.8 1.152v5.412c0 1.369-1.132 2.117-2.292 2.2a1.87 1.87 0 0 1-1.708-.88c.604-.28.8-.72.8-1.088V9.184c0-1.152 1.18-1.968 2.292-1.984");
}

.oba78abop {
  fill: var(--svg-color--ba8318, #ba8318);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w1qt675ia {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.582 9.068c.312 0 .644.16.772.24c-.848-.148-1.765.304-1.809 1.372c-.044 1.072.745 1.508 1.417 1.552a1.22 1.22 0 0 0 1.036-.48c.128 2.68-1.992 3.212-2.905 3.264c-.916.052-3.216-.768-3.088-3.144c.104-1.904 1.2-2.588 1.684-2.696c-.44.556-.54.744-.64 1.44c-.08.552.12 1.16.216 1.36c-.048-.464-.088-.684 0-1.052c.4-1.616 1.472-2.04 1.96-2.052a2.24 2.24 0 0 0-.72 1.464a2 2 0 0 0 .588 1.536a2.4 2.4 0 0 1-.28-1.192c.248-1.536 1.373-1.612 1.769-1.612m6.84 0c-.312 0-.644.16-.772.24c.848-.148 1.768.304 1.808 1.372c.044 1.072-.744 1.508-1.412 1.552a1.22 1.22 0 0 1-1.04-.48c-.128 2.68 1.992 3.212 2.908 3.264c.912.052 3.213-.768 3.08-3.144c-.1-1.904-1.2-2.588-1.68-2.696c.44.556.54.744.64 1.44c.08.552-.12 1.16-.216 1.36c.049-.464.088-.684 0-1.052c-.4-1.616-1.472-2.04-1.96-2.052c.416.38.673.902.72 1.464a2 2 0 0 1-.584 1.536c.268-.544.296-1.02.276-1.192c-.248-1.536-1.372-1.612-1.768-1.612");
}

</style>
