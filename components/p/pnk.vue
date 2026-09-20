<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nqntdfcjo"/><path fill="url(#SVGK8M83b1v)" class="fl-32zl-e"/><defs><linearGradient id="SVGK8M83b1v" x1="19.594" x2="1.577" y1=".469" y2="15.33" gradientUnits="userSpaceOnUse"><stop offset=".08" class="biikg_0ht"/><stop offset=".29" class="jfx4j0b7c"/><stop offset=".74" class="ahw71wttv"/><stop offset=".89" class="etz8zqb0c"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pnk" /></template>
<style>
.ahw71wttv {
  stop-color: var(--svg-color--9d9d9f, #9d9d9f);
}

.biikg_0ht {
  stop-color: var(--svg-color--3e3e40, #3e3e40);
}

.etz8zqb0c {
  stop-color: var(--svg-color--606061, #606061);
}

.fl-32zl-e {
  d: path("m8.287 4.125l9.051.394L21 12.55l-5.17 7.324l-9.1-.574L3 10.611zm6.638 4.624l-6.564 2.823l5.608 4.275zM14.16 7.33L8.917 5.11L7.821 9.784zm-1.328 9.585L7.134 12.91l.141 5.428zm7.257-4.387l-3.882-3.882l-1.023 7.46zm-5.923 5.265L9.362 19.03l5.653.355l-.844-1.592zm5.163-3.505l-4.202 3.083l.833 1.609l3.375-4.692zm-1.985-8.645l-.822 1.653l3.044 3.044zm-1.018-.788l-5.344-.213l4.41 1.895l.934-1.687zm-8.826.76l-3.74 4.652l2.502.523zm-1.39 6.086l-2.514-.523l2.621 6.086l-.112-5.563z");
}

.ft5dv1b6b {
  fill: none;
}

.jfx4j0b7c {
  stop-color: var(--svg-color--5b5b5d, #5b5b5d);
}

.nqntdfcjo {
  fill: var(--svg-color--3b3b3d, #3b3b3d);
  d: path("m8.287 4.125l9.051.394L21 12.55l-5.17 7.324l-9.1-.574L3 10.611z");
}

</style>
