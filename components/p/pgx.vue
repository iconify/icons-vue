<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t--09hbdh"/><path fill="url(#SVGAC9vMedc)" class="rt580od4r"/><defs><linearGradient id="SVGAC9vMedc" x1="5.277" x2="6.775" y1="16.338" y2="20.785" gradientUnits="userSpaceOnUse"><stop class="pi4wvbboj"/><stop offset="1" class="e9ujo-bul"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pgx" /></template>
<style>
.e9ujo-bul {
  stop-color: var(--svg-color--05d8a8, #05d8a8);
}

.ft5dv1b6b {
  fill: none;
}

.pi4wvbboj {
  stop-color: var(--svg-color--202d52, #202d52);
}

.rt580od4r {
  d: path("M8.423 20.105c-.307.697-.94.598-1.323.598c-3.483 0-4.18-1.358-4.093-2.043c.749-2.682 5.805-2.595 6.461-2.595c.528 0 .534.383.47.58z");
}

.t--09hbdh {
  fill: var(--svg-color--03edae, #03edae);
  d: path("M3.483 16.006c.43-.5 1.753-1.104 4.063-1.104h4.21c3.076.006 9.23-1.532 9.23-6.565c.15-1.684-.836-5.045-6.003-5.045s-7.129 1.544-8.011 3.21L3.21 15.855a.153.153 0 0 0 .145.209a.17.17 0 0 0 .128-.058m5.323-4.378l1.295-3.593a.4.4 0 0 1 .07-.116c.348-.412 1.921-1.144 3.442-1.144h.075c1.951 0 3.826 0 3.826 1.521c0 1.544-2.246 3.123-5.062 3.123H9.956c-.442 0-.813.117-1.028.175z");
}

</style>
