<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rq0j2wbhv"/><path class="dps_f8bgl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sylo-background" /></template>
<style>
.dps_f8bgl {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12.141a2.448 2.448 0 0 1-3.387 2.263A2.448 2.448 0 1 1 20 12.141m-1.198 0a1.253 1.253 0 0 0-2.136-.884a1.25 1.25 0 0 0-.367.885a1.252 1.252 0 0 0 2.502 0M5.975 14.59c.99 0 1.752-.435 1.752-1.454v-.016c0-.84-.73-1.21-1.375-1.427c-.492-.168-.93-.293-.93-.547v-.017c0-.179.162-.32.481-.32c.271 0 .623.115.99.293c.07.039.157.06.239.06h.01a.513.513 0 0 0 .509-.515a.53.53 0 0 0-.308-.488a3.16 3.16 0 0 0-1.418-.352c-.925 0-1.677.526-1.677 1.458v.016c0 .894.73 1.192 1.363 1.377c.503.151.937.315.937.598v.015c0 .207-.167.342-.546.342c-.368 0-.8-.135-1.24-.412a.5.5 0 0 0-.253-.065h-.016a.506.506 0 0 0-.493.515a.51.51 0 0 0 .249.444c.508.341 1.109.495 1.726.495m3.359 1.196c.78 0 1.163-.362 1.547-1.294l1.585-3.77a1 1 0 0 0 .06-.31v-.004a.613.613 0 0 0-.617-.6c-.33 0-.519.232-.622.508l-.947 2.588L9.33 10.3c-.107-.31-.296-.493-.62-.493c-.364 0-.645.26-.645.628q.014.153.07.298l1.583 3.559l-.043.103c-.119.233-.227.276-.46.276a.8.8 0 0 1-.276-.048a.7.7 0 0 0-.216-.033h-.005a.52.52 0 0 0-.509.531c0 .32.222.472.411.542c.227.082.47.133.714.123m3.833-1.854c0 .358.24.657.598.657c.357 0 .598-.298.598-.657v-5.05c0-.358-.24-.67-.598-.67c-.357 0-.598.312-.598.67z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rq0j2wbhv {
  fill: var(--svg-color--e5661f, #e5661f);
  d: path("M24 0H0v24h24z");
}

</style>
