<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGJYIlZbgX)" class="m92kw0lwy"/><path fill="url(#SVGIEX6hcZK)" class="u8fq2wg6w"/><path class="ph4oorbeh"/><path class="y19obfg-i"/><path class="heqqgwgau"/><path class="rh8qusfun"/><defs><linearGradient id="SVGJYIlZbgX" x1="20.131" x2="3.887" y1="12.499" y2="11.94" gradientUnits="userSpaceOnUse"><stop class="phufdmery"/><stop offset="1" class="nsqg2ubxa"/></linearGradient><linearGradient id="SVGIEX6hcZK" x1="3.868" x2="14.423" y1="6.259" y2="23.395" gradientUnits="userSpaceOnUse"><stop class="n47g9tfhd"/><stop offset="1" class="w35focbwb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:navi" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.heqqgwgau {
  fill: var(--svg-color--ff7819, #ff7819);
  d: path("M19.929 6.88c.133-.33.202-.685.202-1.042C20.13 4.271 18.83 3 17.227 3s-2.903 1.27-2.903 2.838c0 .349.063.683.181.991c.55 1.803 1.989 3.205 2.707 3.72c1.602-1.18 2.396-2.68 2.717-3.669");
}

.m92kw0lwy {
  d: path("M7.934 13.96L3.87 18.533V5.308a2.032 2.032 0 0 1 4.064 0z");
}

.n47g9tfhd {
  stop-color: var(--svg-color--9cd863, #9cd863);
}

.nsqg2ubxa {
  stop-color: var(--svg-color--8cd037, #8cd037);
}

.ph4oorbeh {
  fill: var(--svg-color--ffc524, #ffc524);
  d: path("m3.874 18.377l4.065-4.825v5.416a2.032 2.032 0 1 1-4.065 0z");
}

.phufdmery {
  stop-color: var(--svg-color--5dc17c, #5dc17c);
}

.rh8qusfun {
  fill: var(--svg-color--ac46bc, #ac46bc);
  d: path("M17.227 7.065a1.162 1.162 0 1 0 .001-2.323a1.162 1.162 0 0 0 0 2.323");
}

.u8fq2wg6w {
  d: path("m7.788 10.693l-.18-6.496L18.82 17.714a1.99 1.99 0 0 1-.288 2.833a2.046 2.046 0 0 1-2.85-.294z");
}

.w35focbwb {
  stop-color: var(--svg-color--49adda, #49adda);
}

.y19obfg-i {
  fill: var(--svg-color--91d450, #91d450);
  d: path("m3.874 5.949l4.065 4.971V5.308a2.032 2.032 0 1 0-4.065 0z");
}

</style>
