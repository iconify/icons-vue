<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGDjxU9S4f)" class="r4i437pya"/><path class="nalvsab6x"/><path class="w5-j3dbxv"/><path class="d8fehpv0n"/><path clip-rule="evenodd" class="isyhkdbji"/></g><defs><linearGradient id="SVGDjxU9S4f" x1="6.772" x2="18.139" y1="8.662" y2="9.761" gradientUnits="userSpaceOnUse"><stop offset=".03" class="yb8_1xb-v"/><stop offset=".08" class="xzj13d2_q"/><stop offset=".32" class="qaerlncod"/><stop offset=".48" class="vod6a7b_i"/><stop offset=".54" class="r-blk6b-g"/><stop offset=".57" class="pr2-lbrum"/><stop offset=".61" class="oi1iq13_o"/><stop offset=".72" class="w2_30xbnu"/><stop offset=".85" class="eoz9wmwmt"/><stop offset="1" class="xm9ai-bsh"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rail-background" /></template>
<style>
.d8fehpv0n {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.6 14.089c.235-.269.658-.998.475-1.789c-.18-.8-.541-2.334-.701-2.997c-.17-.588-.273-2.01.705-2.984c.97-.974 1.215-1.214 1.37-1.364c-.268.376-.47 1.049-.396 1.967q.187 1.59.532 3.153c.188.555.264 1.938-.86 3.073c.202-.532.498-1.577.329-2.335a72 72 0 0 0-.631-2.56c-.07-.376-.193-1.256-.08-1.74c-.113.267-.268 1.067 0 2.131s.457 2.038.518 2.39c.094.598.094 1.954-.66 2.589c.189-.33.504-1.299.222-2.475a25 25 0 0 0-.221-.848c-.363-1.303-.767-2.767-.127-3.783c-.264.25-.734 1.063-.475 2.306q.283 1.368.602 2.73c.16.625.259 2.009-.602 2.536m-4.283 4.127c.235-.268.659-.998.475-1.793c-.178-.8-.54-2.33-.7-2.998c-.17-.588-.274-2.005.7-2.979c.975-.974 1.534-1.524 1.694-1.68c-.272.377-.79 1.365-.715 2.283c.08.917.386 2.48.532 3.148c.188.555.263 1.939-.861 3.073c.202-.527.494-1.576.33-2.33a77 77 0 0 0-.631-2.564c-.076-.377-.193-1.252-.08-1.732c-.113.264-.273 1.064 0 2.127a37 37 0 0 1 .517 2.39c.094.598.094 1.954-.659 2.589c.189-.334.504-1.299.222-2.476c-.062-.268-.142-.555-.222-.846c-.362-1.304-.767-2.767-.127-3.784c-.263.25-.734 1.064-.475 2.306q.284 1.368.602 2.73c.156.625.26 2.009-.602 2.536m-4.15-2.861l1.778-1.756c-1.04 1.247-.593 3.313-.24 4.189l-.96-1.271l-.136-1.162l-.122 1.162zm12.668-5.553c.216-.433.57-1.54.268-2.494l.833.847c-.028.282-.179.908-.55 1.157c.131-.268.371-.894.282-1.266l-.283-.188c.07.466.066 1.515-.55 1.948z");
}

.eoz9wmwmt {
  stop-color: var(--svg-color--6e6662, #6e6662);
}

.ft5dv1b6b {
  fill: none;
}

.isyhkdbji {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.47a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

.nalvsab6x {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.793 10.39c.268-.236.997-.66 1.788-.476c.8.179 2.33.541 2.998.701c.588.17 2.009.273 2.983-.706q.736-.717 1.398-1.505a3.02 3.02 0 0 1-2 .531a32 32 0 0 1-3.153-.531a3.16 3.16 0 0 0-3.073.86c.532-.202 1.576-.498 2.334-.329c.819.18 2.047.495 2.56.631c.377.07 1.256.193 1.736.08c-.263.113-1.063.273-2.127 0q-1.188-.3-2.395-.518c-.598-.094-1.948-.094-2.588.66a3.68 3.68 0 0 1 2.48-.222c.268.061.55.141.847.221c1.299.362 2.767.767 3.784.127c-.255.264-1.069.734-2.306.476a104 104 0 0 1-2.73-.603c-.63-.16-2.01-.259-2.536.602m-3.981 4.437c.268-.235.997-.659 1.792-.475c.796.179 2.33.541 2.993.696c.589.174 2.01.278 2.984-.696s1.525-1.539 1.68-1.694c-.377.268-1.365.79-2.282.71a32 32 0 0 1-3.153-.532a3.16 3.16 0 0 0-3.073.866c.531-.202 1.576-.498 2.334-.329c.819.179 2.047.494 2.565.626c.376.075 1.251.197 1.731.085c-.263.113-1.063.268-2.127 0q-1.186-.3-2.39-.518c-.598-.094-1.953-.094-2.589.659a3.68 3.68 0 0 1 2.476-.226c.268.066.555.141.847.226c1.303.357 2.767.767 3.783.127c-.25.263-1.063.73-2.306.47a91 91 0 0 1-2.729-.597c-.626-.16-2.01-.26-2.536.602");
}

.oi1iq13_o {
  stop-color: var(--svg-color--7e7873, #7e7873);
}

.pr2-lbrum {
  stop-color: var(--svg-color--0f0c0d, #0f0c0d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qaerlncod {
  stop-color: var(--svg-color--110e0e, #110e0e);
}

.r-blk6b-g {
  stop-color: var(--svg-color--0f0d0d, #0f0d0d);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vod6a7b_i {
  stop-color: var(--svg-color--979492, #979492);
}

.w2_30xbnu {
  stop-color: var(--svg-color--c8c7c7, #c8c7c7);
}

.w5-j3dbxv {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.365 6.47L6.377 17.444l.438.292L17.789 6.913z");
}

.xm9ai-bsh {
  stop-color: var(--svg-color--0a0808, #0a0808);
}

.xzj13d2_q {
  stop-color: var(--svg-color--908d89, #908d89);
}

.yb8_1xb-v {
  stop-color: var(--svg-color--100e0e, #100e0e);
}

</style>
