<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG6tjX6bzq)" class="r4i437pya"/><path clip-rule="evenodd" class="xyp-yuxrz"/></g><defs><linearGradient id="SVG6tjX6bzq" x1="16.473" x2="6.826" y1="5.647" y2="18.118" gradientUnits="userSpaceOnUse"><stop class="kv7dhf4cl"/><stop offset=".47" class="vc9l84o9y"/><stop offset="1" class="clahyacng"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:woof-background" /></template>
<style>
.clahyacng {
  stop-color: var(--svg-color--c13af3, #c13af3);
}

.ft5dv1b6b {
  fill: none;
}

.kv7dhf4cl {
  stop-color: var(--svg-color--1fdeb1, #1fdeb1);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vc9l84o9y {
  stop-color: var(--svg-color--6a91d0, #6a91d0);
}

.xyp-yuxrz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.532 12a7.53 7.53 0 0 1-7.53 7.53h-.037c-.137-1.365-.636-2.42-.904-2.824l.236-1.412l.705-.941v-.706l.941-1.412l-.235-.235l-.235.235l.235-.706v-.705c0-.565-.786-1.022-1.176-1.177l-2.118 1.647c-.315-.08-1.318 0-2.823.941c-.791.494-1.182 1.742-1.356 3.069A7.53 7.53 0 1 1 19.532 12M5.155 16.141a8 8 0 1 1 4.88 3.614a8 8 0 0 1-4.88-3.619zm2.73.8c-.98-.758-.937-2.273-.353-3.294c-.236.706-.518 1.713.14 2.734c.034-.245.09-.598.175-.979c.141-.616.4-1.294.861-1.755c-.348.348-.461.946-.565 1.464l-.065.343c-.057.254-.132.913-.17 1.261zm7.882-5.412c1.558 0 2.823-.945 2.823-2.117s-1.265-2.118-2.823-2.118s-2.823.946-2.823 2.118c0 .437.173.842.48 1.176h-.01l-.235 1.177l1.1-.55a3.6 3.6 0 0 0 1.488.314m1.732-2.117h.15v-.236h-.15v-.009c.01-.08.014-.165.108-.165h.042v-.296h-.066a.44.44 0 0 0-.31.103c-.07.066-.094.175-.094.302v.065h-.113v.236h.113v.706h.32zm-3.21.706h.372l.24-.942h-.31l-.104.598l-.141-.598h-.358l-.141.593l-.104-.593h-.329l.235.942h.377l.132-.612zm.654-.471c0 .287.198.47.495.47c.291 0 .494-.183.494-.47c0-.282-.203-.47-.494-.47c-.292 0-.495.188-.495.47m.655 0c0 .132-.066.235-.16.235c-.095 0-.16-.094-.16-.235c0-.136.07-.235.16-.235c.089 0 .16.103.16.235m.908.47c-.292 0-.494-.183-.494-.47c0-.282.207-.47.498-.47c.288 0 .494.188.494.47c0 .287-.206.47-.498.47m0-.235c.094 0 .165-.103.165-.235s-.071-.235-.16-.235c-.095 0-.16.099-.16.235c0 .141.065.235.155.235");
}

</style>
