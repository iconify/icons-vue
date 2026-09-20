<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eokb-tbaq"/><path clip-rule="evenodd" class="ce1neybdf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usdc-background" /></template>
<style>
.ce1neybdf {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20c4.435 0 8-3.565 8-8s-3.565-8-8-8s-8 3.565-8 8s3.565 8 8 8m2.2-6.735c0-1.165-.7-1.565-2.1-1.73c-1-.135-1.2-.4-1.2-.87c0-.465.335-.765 1-.765c.6 0 .935.2 1.1.7c.035.1.135.165.235.165h.53c.135 0 .235-.1.235-.23v-.036c-.135-.734-.735-1.434-1.5-1.5v-.734c0-.135-.1-.235-.265-.265h-.44c-.135 0-.26.1-.295.265V9c-1 .135-1.665.9-1.665 1.735c0 1.1.665 1.53 2.065 1.7c.935.165 1.235.365 1.235.9c0 .53-.47.9-1.1.9c-.87 0-1.17-.37-1.27-.87c-.03-.13-.13-.2-.23-.2h-.57c-.13 0-.23.1-.23.235v.035c.13.83.665 1.4 1.765 1.565v.74c0 .135.1.224.265.26h.48c.13 0 .22-.09.255-.26V15c1-.165 1.7-.835 1.7-1.735m-5.566 2.49c.483.443 1.05.786 1.666 1.01c.1.07.2.2.2.3v.47c0 .064 0 .1-.035.13c-.03.134-.165.2-.3.134a6 6 0 0 1 0-11.435c.035-.03.1-.03.135-.03c.135.03.2.13.2.265v.465c0 .17-.065.27-.2.335a4.93 4.93 0 0 0-2.965 2.965a4.965 4.965 0 0 0 1.299 5.391M13.535 6.5c.03-.135.165-.2.3-.135a6.05 6.05 0 0 1 3.9 3.935c1 3.165-.735 6.535-3.9 7.535c-.035.03-.1.03-.135.03c-.135-.03-.2-.13-.2-.265v-.465c0-.17.065-.27.2-.335a4.93 4.93 0 0 0 2.965-2.965a4.967 4.967 0 0 0-2.965-6.4c-.1-.07-.2-.2-.2-.335v-.465c0-.07 0-.1.035-.135");
}

.eokb-tbaq {
  fill: var(--svg-color--0b53bf, #0b53bf);
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
