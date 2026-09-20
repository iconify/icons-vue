<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG3IVuObYJ)" class="r4i437pya"/><path class="nfv1_3bxi"/><path class="asgu0rbyh"/><path class="qb3lruhrd"/></g><defs><linearGradient id="SVG3IVuObYJ" x1="12" x2="12" y1="0" y2="24" gradientUnits="userSpaceOnUse"><stop class="gjjq5bbah"/><stop offset="1" class="jjzeugb2r"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:six-background" /></template>
<style>
.asgu0rbyh {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.2 17.324V12.67c0-.3.223-.266.334-.21c.36.174 1.043.531 1.147.582s.121.184.12.243c-.005.343-.011 3.116 0 3.35s.129.324.185.34l2.796 1.39a.58.58 0 0 0 .39 0l2.847-1.39c.164-.09.181-.265.18-.34c.003-.958.005-3.206 0-3.434c-.004-.227-.114-.328-.18-.35c-.878-.428-2.769-1.295-2.871-1.358c-.103-.063-.27-.027-.342 0l-.342.177c-.118.074-.257.03-.312 0l-1.368-.683c-.176-.136-.073-.267 0-.315c.505-.259 1.587-.804 1.875-.918s.609-.047.733 0c1.259.619 3.84 1.898 4.1 2.064s.316.506.308.641v4.85c-.014.37-.32.582-.465.642c-1.2.597-3.677 1.827-3.982 1.97a.9.9 0 0 1-.738 0a444 444 0 0 1-4.081-2.023a.66.66 0 0 1-.334-.575");
}

.ft5dv1b6b {
  fill: none;
}

.gjjq5bbah {
  stop-color: var(--svg-color--25a7df, #25a7df);
}

.jjzeugb2r {
  stop-color: var(--svg-color--655ba7, #655ba7);
}

.nfv1_3bxi {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.8 6.676v2.789c0 .3-.223.265-.334.21c-.36-.174-1.043-.542-1.147-.592s-.121-.184-.12-.244V7.326c-.01-.234-.129-.324-.185-.34a129 129 0 0 0-2.821-1.35a.6.6 0 0 0-.39 0c-.837.414-2.627 1.259-2.792 1.35a.42.42 0 0 0-.21.34v3.359c.004.227.145.328.21.35c.878.428 2.739 1.3 2.841 1.362s.27.027.342 0l.342-.177c.118-.074.257-.03.312 0l1.368.683c.176.137.073.267 0 .315c-.505.259-1.587.804-1.875.918a1.1 1.1 0 0 1-.733 0c-1.259-.619-3.84-1.898-4.1-2.064s-.316-.478-.308-.613V6.69c.014-.37.32-.582.465-.642c1.2-.597 3.677-1.827 3.982-1.97a.9.9 0 0 1 .738 0A450 450 0 0 1 16.466 6.1a.65.65 0 0 1 .334.576");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qb3lruhrd {
  fill: var(--svg-color--fdd35a, #fdd35a);
  d: path("M9.601 16.38v-2.232c0-.19.108-.155.181-.122c.674.301 2.037.912 2.101.944a.2.2 0 0 0 .162 0a380 380 0 0 0 2.153-.944c.169-.079.205.049.201.122a288 288 0 0 0 0 2.232c.004.077-.052.137-.08.158c-.693.321-2.1.977-2.2 1.03a.3.3 0 0 1-.255 0c-.653-.293-1.992-.894-2.123-.946s-.148-.183-.14-.242");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
