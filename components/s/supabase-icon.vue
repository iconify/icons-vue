<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":263};
const content = `<defs><linearGradient id="SVGMPst3dYn" x1="20.862%" x2="63.426%" y1="20.687%" y2="44.071%"><stop offset="0%" class="vmjwiuq4d"/><stop offset="100%" class="dkd-0gk2d"/></linearGradient><linearGradient id="SVGNaiFRdXR" x1="1.991%" x2="21.403%" y1="-13.158%" y2="34.708%"><stop offset="0%"/><stop offset="100%" class="k05n1gbkm"/></linearGradient></defs><path fill="url(#SVGMPst3dYn)" class="v6lwc-bqj"/><path fill="url(#SVGNaiFRdXR)" class="qkt0t5jfo"/><path class="a8a2lhb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:supabase-icon" /></template>
<style>
.a8a2lhb_j {
  fill: var(--svg-color--3ecf8e, #3ecf8e);
  d: path("M106.399 4.37c6.717-8.461 20.338-3.826 20.5 6.976l1.037 157.984H23.037c-19.241 0-29.973-22.223-18.008-37.292z");
}

.dkd-0gk2d {
  stop-color: var(--svg-color--3ecf8e, #3ecf8e);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.qkt0t5jfo {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M149.602 258.579c-6.718 8.46-20.338 3.824-20.5-6.977l-2.367-157.984h106.229c19.24 0 29.971 22.223 18.007 37.292z");
}

.v6lwc-bqj {
  d: path("M149.602 258.579c-6.718 8.46-20.338 3.824-20.5-6.977l-2.367-157.984h106.229c19.24 0 29.971 22.223 18.007 37.292z");
}

.vmjwiuq4d {
  stop-color: var(--svg-color--249361, #249361);
}

</style>
