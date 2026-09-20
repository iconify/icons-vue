<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<defs><linearGradient id="SVGAzz3ndTH" x1="81.562%" x2="-18.086%" y1="44.842%" y2="44.842%"><stop offset="0%" class="lppieibrp"/><stop offset="100%" class="aidlx9b9t"/></linearGradient></defs><path class="u7ifbgmgw"/><path class="ffcz7ibbm"/><path class="nxagj0bap"/><path class="bvc19rbmz"/><path class="wi0rl_yyq"/><path class="k9k8gebxt"/><path class="v-i_-7-0t"/><path class="tmzpbcb6i"/><path fill="url(#SVGAzz3ndTH)" class="cgmattbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:qdrant-icon" /></template>
<style>
.aidlx9b9t {
  stop-color: var(--svg-color--c91540, #c91540);
  stop-opacity: 0;
}

.bvc19rbmz {
  fill: var(--svg-color--24386c, #24386c);
  d: path("m156.857 202.807l-28.856 42.54v50.256l40.946-23.625l21.097-31.503");
}

.cgmattbsi {
  d: path("M128.019 245.363v-50.264l-40.733-23.442v50.18z");
}

.ffcz7ibbm {
  fill: var(--svg-color--7589be, #7589be);
  d: path("M255.995 73.9L212.47 99.037l-89.82-19.702L17.516 122.14L0 73.9l63.988-36.95L127.996 0l63.99 36.95z");
}

.k9k8gebxt {
  fill: var(--svg-color--b2bfe8, #b2bfe8);
  d: path("m87.056 124.179l40.945 23.625v47.288l-37.869 1.629l-22.907-29.25z");
}

.lppieibrp {
  stop-color: var(--svg-color--ff3364, #ff3364);
}

.nxagj0bap {
  fill: var(--svg-color--b2bfe8, #b2bfe8);
  d: path("m.003 73.9l43.525 25.137l25.231 75.037l85.19 68.162l-25.948 53.363l-64.008-36.952l-63.99-36.95V73.898");
}

.tmzpbcb6i {
  fill: var(--svg-color--dc244c, #dc244c);
  d: path("m168.947 271.975l43.525 23.626V99.04l-42.245-24.38L128 50.276L85.756 74.658L43.53 99.04v97.542l42.226 24.381l42.245 24.383l40.946-23.646zm0-100.531L128 195.088l-40.945-23.644v-47.269L128 100.531l40.946 23.644z");
}

.u7ifbgmgw {
  fill: var(--svg-color--24386c, #24386c);
  d: path("m201.317 271.722l-5.894-162.509l-10.675-42.845L256 73.911v196.582l-43.525 25.12z");
}

.v-i_-7-0t {
  fill: var(--svg-color--24386c, #24386c);
  d: path("m128.001 147.8l40.946-23.623l27.866 46.4l-33.722 27.862l-35.09-3.35z");
}

.wi0rl_yyq {
  fill: var(--svg-color--7589be, #7589be);
  d: path("m128.019 195.107l-40.963-70.922l8.823-23.507l33.542-16.262l39.525 39.77z");
}

</style>
