<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGsbayVb3w)" class="r4i437pya"/><path class="bid2hxbbe"/></g><defs><linearGradient id="SVGsbayVb3w" x1="12" x2="12" y1="10" y2="14" gradientUnits="userSpaceOnUse"><stop class="icj9zfbuh"/><stop offset="1" class="eg5tqzbiw"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:realm-background" /></template>
<style>
.bid2hxbbe {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.5 13.997l.227-.457L12.5 10l.667 1.327l.666 1.34h-.716c-.03 0-.04-.007-.05-.027l-.44-.883l-.11-.217l-.014-.027l-.006-.01l-.007.01l-.013.024l-.277.553l-.61 1.217l-.34.666q-.012.022-.033.024zm4 0h-.717c-.013 0-.033-.007-.036-.017l-.314-.627l-.003-.01l-.003-.006h.71c.016 0 .033 0 .043.016l.313.627l.007.02zM20 14h-.667v-2.387l-.673.674c-.217.223-.433.44-.657.66l-.096-.094l-.294-.296l-1.593-1.607a.07.07 0 0 1-.02-.04V10l.493.493L18.007 12l.006-.01l1.977-1.98L20 10zM4 10.003h1.793c.404 0 .734.15 1.007.44a1.3 1.3 0 0 1 .22 1.457c-.14.295-.383.529-.683.657q-.007-.002-.014.006l-.01.004L7.147 14H6.4c-.023 0-.033-.007-.047-.027c-.133-.23-.273-.456-.41-.686c-.26-.427-.516-.85-.756-1.287H5.8a.69.69 0 0 0 .667-.59c.046-.393-.274-.68-.54-.723l-.02-.004a1 1 0 0 0-.134-.016H4.507c-.084 0-.13-.03-.167-.09l-.217-.367l-.1-.17l-.016-.02L4 10.01zm10.667 0V14h2.666v-.667h-2v-3.33zm-7 2.33v-.666h2.666v.666zm.033 1.584c-.03.023-.04.046-.03.083h2.663v-.667H8.36a.1.1 0 0 0-.05.02l-.27.25l-.343.314zM10.333 10v.667H8.36a.1.1 0 0 1-.05-.017l-.527-.53l-.11-.11l-.006-.01z");
}

.eg5tqzbiw {
  stop-color: var(--svg-color--f8b4c1, #f8b4c1);
}

.ft5dv1b6b {
  fill: none;
}

.icj9zfbuh {
  stop-color: var(--svg-color--b29afa, #b29afa);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
