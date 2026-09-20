<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGrIxS3rVY)" class="bdq2qbc8n"/><path fill="url(#SVGzMAGdbvj)" class="vbjwylbix"/><defs><linearGradient id="SVGrIxS3rVY" x1="5.206" x2="10.404" y1="8.25" y2="19.899" gradientUnits="userSpaceOnUse"><stop class="lrxp2fb9w"/><stop offset=".13" class="mgur39bvh"/><stop offset=".258" class="ss2ufhbeu"/><stop offset=".376" class="f9cro4egm"/><stop offset=".492" class="eojwqixaj"/><stop offset=".612" class="zgxo820li"/><stop offset=".731" class="ahe1014pz"/><stop offset=".829" class="bdukn1b5f"/><stop offset="1" class="l77ol0bwj"/></linearGradient><linearGradient id="SVGzMAGdbvj" x1="19.866" x2="13.566" y1="15.825" y2="6.825" gradientUnits="userSpaceOnUse"><stop class="lrxp2fb9w"/><stop offset=".13" class="mgur39bvh"/><stop offset=".258" class="ss2ufhbeu"/><stop offset=".376" class="f9cro4egm"/><stop offset=".492" class="eojwqixaj"/><stop offset=".612" class="zgxo820li"/><stop offset=".731" class="ahe1014pz"/><stop offset=".829" class="bdukn1b5f"/><stop offset="1" class="l77ol0bwj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:swap" /></template>
<style>
.ahe1014pz {
  stop-color: var(--svg-color--00b9fa, #00b9fa);
}

.bdq2qbc8n {
  d: path("M7.5 9.616v1.034l3.15-2.25L7.5 6.375v.92a4.95 4.95 0 0 0 .45 9.88c1.134 0 2.7-.399 3.6-1.35c1.125-1.299 2.466-4.57 2.466-4.57L9.999 13.86a2.59 2.59 0 0 1-4.165-.403A2.59 2.59 0 0 1 7.5 9.616");
}

.bdukn1b5f {
  stop-color: var(--svg-color--00c5fb, #00c5fb);
}

.eojwqixaj {
  stop-color: var(--svg-color--009df9, #009df9);
}

.f9cro4egm {
  stop-color: var(--svg-color--008bf9, #008bf9);
}

.ft5dv1b6b {
  fill: none;
}

.l77ol0bwj {
  stop-color: var(--svg-color--00ccfc, #00ccfc);
}

.lrxp2fb9w {
  stop-color: var(--svg-color--0076ef, #0076ef);
}

.mgur39bvh {
  stop-color: var(--svg-color--007ff6, #007ff6);
}

.ss2ufhbeu {
  stop-color: var(--svg-color--0084f6, #0084f6);
}

.vbjwylbix {
  d: path("M16.5 14.384V13.35l-3.15 2.25l3.15 2.025v-.92a4.95 4.95 0 0 0-.45-9.88c-1.134 0-2.7.399-3.6 1.35c-1.125 1.299-2.466 4.57-2.466 4.57L14 10.14a2.587 2.587 0 1 1 2.499 4.243");
}

.zgxo820li {
  stop-color: var(--svg-color--00aef9, #00aef9);
}

</style>
