<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xpfr6bc8m"/><path class="nu1a0mbto"/><path class="acxmifogh"/><path class="gf4n4_bjz"/><path class="ohn71uxex"/><path class="mf2_jqbho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-word-spacing-sharp-duotone" /></template>
<style>
.acxmifogh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 8V10H8V8H13ZM22 8V10H15V8H22ZM13 2V4H2V2H13Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gf4n4_bjz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 2V4H15V2H22Z");
}

.mf2_jqbho {
  d: path("M22 8V10H15V8H22ZM22 2V4H15V2H22Z");
}

.nu1a0mbto {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 14V16H11V14H22ZM6 8V10H2V8H6Z");
}

.ohn71uxex {
  d: path("M22 14V16H11V14H22ZM13 8V10H8V8H13Z");
}

.xpfr6bc8m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 20V22H2V20H13ZM9 14V16H2V14H9Z");
}

</style>
