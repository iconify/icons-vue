<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGYQlaCcrW)" class="r3eiiy6xl"/><path fill="url(#SVGAItScecz)" class="pub8lib9s"/><path fill="url(#SVG2B9hGcqF)" class="ezzuhx25l"/><path fill="url(#SVGsslLxdaF)" class="byxcsmxcx"/><defs><linearGradient id="SVGYQlaCcrW" x1="3" x2="21" y1="8.4" y2="15.983" gradientUnits="userSpaceOnUse"><stop class="ekadlobcu"/><stop offset="1" class="cqxfv7j9h"/></linearGradient><linearGradient id="SVGAItScecz" x1="3.205" x2="22.547" y1="7.868" y2="16.606" gradientUnits="userSpaceOnUse"><stop class="vx1js0b6p"/><stop offset="1" class="lbzl1uvri"/></linearGradient><linearGradient id="SVG2B9hGcqF" x1="3" x2="21" y1="8.401" y2="15.984" gradientUnits="userSpaceOnUse"><stop class="jugtbfbot"/><stop offset="1" class="mdz7bx6xe"/></linearGradient><linearGradient id="SVGsslLxdaF" x1="7.8" x2="12.6" y1="12.841" y2="14.863" gradientUnits="userSpaceOnUse"><stop class="h3_ktxb2s"/><stop offset="1" class="tr5oynb_z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pixel" /></template>
<style>
.byxcsmxcx {
  d: path("M7.8 11.401h4.8v4.8H7.8z");
}

.cqxfv7j9h {
  stop-color: var(--svg-color--16ddde, #16ddde);
}

.ekadlobcu {
  stop-color: var(--svg-color--3eff6e, #3eff6e);
}

.ezzuhx25l {
  d: path("M3 11.401h4.8v4.8H3z");
}

.ft5dv1b6b {
  fill: none;
}

.h3_ktxb2s {
  stop-color: var(--svg-color--e059fe, #e059fe);
}

.jugtbfbot {
  stop-color: var(--svg-color--ff6f3f, #ff6f3f);
}

.lbzl1uvri {
  stop-color: var(--svg-color--ff3196, #ff3196);
}

.mdz7bx6xe {
  stop-color: var(--svg-color--ffc546, #ffc546);
}

.pub8lib9s {
  d: path("M12.6 3h1.878C18.078 3 21 5.922 21 9.528c0 3.6-2.922 6.672-6.528 6.672H7.8v-9h4.8v4.2h1.878c1.182 0 2.322-.918 2.322-2.1s-1.14-2.1-2.328-2.1H12.6z");
}

.r3eiiy6xl {
  d: path("M7.8 16.2h4.8V21H7.8z");
}

.tr5oynb_z {
  stop-color: var(--svg-color--656fff, #656fff);
}

.vx1js0b6p {
  stop-color: var(--svg-color--ff5b3c, #ff5b3c);
}

</style>
