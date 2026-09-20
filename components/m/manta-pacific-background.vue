<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9ldxXdFl)" class="r4i437pya"/><path clip-rule="evenodd" class="h2u8pabbr"/></g><defs><linearGradient id="SVG9ldxXdFl" x1="3.857" x2="20.143" y1="12.148" y2="11.85" gradientUnits="userSpaceOnUse"><stop class="cgzdpwb5o"/><stop offset=".49" class="otegc2b8w"/><stop offset="1" class="d8vw4dhcb"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:manta-pacific-background" /></template>
<style>
.cgzdpwb5o {
  stop-color: var(--svg-color--29ccb9, #29ccb9);
}

.d8vw4dhcb {
  stop-color: var(--svg-color--ff66b7, #ff66b7);
}

.ft5dv1b6b {
  fill: none;
}

.h2u8pabbr {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.72 17.738A7.158 7.158 0 0 1 12 4.843c3.263 0 6.826 1.949 7.687 4.935A8 8 0 1 0 20 12v-.421h-.498a14 14 0 0 1-.966-.051c-.6-.053-1.285-.154-1.75-.34c-.75-.3-1.174-.697-1.658-1.162L15.1 10c-.485-.465-1.03-.988-1.973-1.433c-.93-.437-1.958-.367-2.714-.211a7 7 0 0 0-1.221.375c-.38.16-.75.35-1.123.525c0 0 .732.2 1.094.313q.145.045.288.104q.36.145.69.353c.39.251.714.567.847.955c-.83.109-1.607.473-2.188.815a9 9 0 0 0-1.092.76c-.048.039-.797.698-.797.698s.966.103 1.443.2c.317.063.744.166 1.19.321c.448.157.9.361 1.276.624c.376.262.652.566.788.913c.396 1.012.007 1.999-.773 2.553c-.77.548-1.943.678-3.115-.126m2.73 1.252a3.2 3.2 0 0 0 .873-.44c1.062-.754 1.62-2.137 1.07-3.546c-.218-.553-.631-.976-1.09-1.297c-.461-.321-.991-.557-1.481-.728a10 10 0 0 0-.907-.265q.153-.1.311-.193c.649-.381 1.465-.732 2.247-.732c1.18 0 2.059.363 2.898.751l.23.107c.75.352 1.537.721 2.451.721a4.26 4.26 0 0 0 2.055-.51a7.16 7.16 0 0 1-8.658 6.131m7.747-6.649a3.5 3.5 0 0 1-1.145.185c-.717 0-1.334-.287-2.116-.652l-.211-.098c-.784-.363-1.69-.748-2.871-.817c-.158-.782-.75-1.316-1.258-1.642l-.169-.103l.156-.035c.681-.14 1.496-.175 2.185.15c.818.384 1.28.828 1.76 1.289l.016.016c.494.474 1.017.971 1.929 1.335c.506.203 1.162.312 1.724.372");
}

.otegc2b8w {
  stop-color: var(--svg-color--0091ff, #0091ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
